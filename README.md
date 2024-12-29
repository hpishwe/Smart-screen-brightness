<h1>Smart Brightness Control Using Hand Gestures</h1>
    <p>
        This project implements a <strong>smart brightness control system</strong> using Python and OpenCV. 
        By utilizing hand gesture recognition, users can dynamically adjust their screen brightness in real-time 
        without the need for physical buttons or keyboard shortcuts.
    </p>

   <h2>Features</h2>
    <ul>
        <li><strong>Real-time Hand Gesture Detection</strong>: Detects hand movements using a webcam.</li>
        <li><strong>Brightness Adjustment</strong>: Adjusts the screen brightness based on hand gestures.</li>
        <li><strong>User-Friendly Interface</strong>: Provides a smooth and interactive experience.</li>
        <li><strong>Customizable Sensitivity</strong>: Fine-tune the system to respond better to specific gestures.</li>
    </ul>

  <h2>How It Works</h2>
    <ol>
        <li><strong>Hand Detection:</strong>
            <ul>
                <li>The program uses OpenCV to detect the hand in the webcam feed.</li>
                <li>The hand contour is tracked and key points are extracted (e.g., distance between fingers).</li>
            </ul>
        </li>
        <li><strong>Gesture Recognition:</strong>
            <ul>
                <li>Specific gestures, such as opening or closing the hand, are used to adjust the brightness.</li>
                <li>The brightness level is calculated based on the distance between the thumb and index finger.</li>
            </ul>
        </li>
        <li><strong>Brightness Control:</strong>
            <ul>
                <li>The system interacts with the operating system to change screen brightness dynamically.</li>
            </ul>
        </li>
    </ol>

   <h2>Installation</h2>
    <h3>1. Prerequisites</h3>
    <p>Ensure you have the following installed:</p>
    <ul>
        <li>Python 3.7 or higher</li>
        <li>pip (Python package manager)</li>
        <li>OpenCV library</li>
    </ul>

  <h3>2. Clone the Repository</h3>
    <pre class="code-block">
git clone https://github.com/hpishwe/Smart-screen-brightness.git
cd Smart-screen-brightness
    </pre>

  <h3>3. Install Dependencies</h3>
    <pre class="code-block">
pip install -r requirements.txt
    </pre>

   

   <h3>2. Adjust Brightness</h3>
    <ul>
        <li>Place your hand in front of the webcam.</li>
        <li>Use the distance between your thumb and index finger to increase or decrease brightness:</li>
        <ul>
            <li><strong>Increase Brightness:</strong> Spread your fingers apart.</li>
            <li><strong>Decrease Brightness:</strong> Bring your fingers closer.</li>
        </ul>
    </ul>

   

   <h2>Dependencies</h2>
    <p>This project uses the following libraries:</p>
    <ul>
        <li><strong>OpenCV:</strong> For hand tracking and video feed processing.</li>
        <li><strong>NumPy:</strong> For numerical operations on image arrays.</li>
        <li><strong>pyautogui</strong> (optional): For system interaction (e.g., controlling brightness on supported platforms).</li>
    </ul>

  
   <h2>Troubleshooting</h2>
    <ol>
        <li><strong>Brightness is not adjusting:</strong>
            <ul>
                <li>Ensure the system supports programmatic brightness adjustment.</li>
                <li>Install <code>pyautogui</code> or similar libraries if needed.</li>
            </ul>
        </li>
        <li><strong>Hand detection is inaccurate:</strong>
            <ul>
                <li>Improve lighting conditions and avoid background clutter.</li>
                <li>Adjust the HSV range in the code to better suit your environment.</li>
            </ul>
        </li>
        <li><strong>Script crashes:</strong>
            <ul>
                <li>Check if the camera is properly connected and accessible.</li>
            </ul>
        </li>
    </ol>

   <h2>Future Improvements</h2>
    <ul>
        <li>Add support for gesture-based volume control.</li>
        <li>Implement AI/ML models for more accurate hand gesture recognition.</li>
        <li>Enhance the GUI for a better user experience.</li>
        <li>Support brightness adjustment for external monitors.</li>
    </ul>

   
