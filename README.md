<h1 align="center">😷 Face Mask Detection System 🎯</h1>
<h3 align="center">Real-Time Detection using OpenCV and Deep Learning</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Face%20Mask%20Detection-blue?style=for-the-badge" alt="Project Type" />
  <img src="https://img.shields.io/badge/Technology-OpenCV%20%7C%20Deep%20Learning-orange?style=for-the-badge" alt="Technology" />
  <img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge" alt="Status" />
</p>

---

<h2>📌 Overview</h2>

<p>
  This project implements a real-time face mask detection system. It identifies faces and determines whether the person is wearing a mask or not — ensuring safety and compliance in crowded or high-risk environments.
</p>

---

<h2>🔧 System Workflow</h2>

<p>The system integrates computer vision and deep learning to achieve accurate mask detection:</p>

<ul>
  <li><b>Face Detection:</b> Utilizes OpenCV’s <b>Haar Cascade Classifier</b> for efficient face detection.</li>
  <li><b>Mask Classification:</b> A pre-trained CNN model classifies the detected face as "Masked" or "Unmasked."</li>
  <li><b>Live Feed Support:</b> Works with webcam input to monitor and classify faces in real time.</li>
</ul>

<p>🛡️ <b>Safety First:</b> Unmasked faces are highlighted, making it easy to spot those without masks.</p>

---

<h2>🚀 Features</h2>

<ul>
  <li>✅ <b>Real-Time Detection:</b> Instantly detects masks on faces from webcam input.</li>
  <li>✅ <b>Accurate Classification:</b> Deep learning ensures high accuracy.</li>
  <li>✅ <b>Color-Coded Output:</b> Green for "Mask On", Red for "No Mask."</li>
  <li>✅ <b>Lightweight Setup:</b> Requires minimal setup and runs on most systems.</li>
</ul>

---

<h2>⚙️ Installation & Usage</h2>

<h3>📥 Install Dependencies</h3>
<pre><code>pip install opencv-python numpy tensorflow</code></pre>

<h3>🔧 Download Haar Cascade Classifier</h3>
<p>Download the missing classifier file from OpenCV's repository:</p>
👉 <a href="https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml" target="_blank"><b>Download haarcascade_frontalface_default.xml</b></a>  
Place the file in the project directory.

<h3>🚀 Run the System</h3>
<pre>run each cell one by one from <b>Face-mask-detection.ipynb</b></pre>

---

<h2>🧠 How It Works</h2>

<ol>
  <li>🔍 <b>Face Detection:</b> Haar Cascade detects faces in the video feed.</li>
  <li>🎯 <b>Mask Classification:</b> The CNN model classifies each detected face as "Masked" or "No Mask."</li>
  <li>🔴🟢 <b>Output Display:</b>  
    - Green box = Mask On  
    - Red box = No Mask  
  </li>
</ol>

---

<h2>🔍 Future Improvements</h2>

<p>For better performance, consider these enhancements:</p>

<ul>
  <li>⚡ Enhance accuracy on partially visible faces.</li>
  <li>📱 Develop a mobile-friendly version.</li>
  <li>🔧 Optimize the model for faster inference on low-end devices.</li>
  <li>🎯 Add support for multiple people in a single frame.</li>
</ul>

---

<h2>🔧 Technologies Used</h2>

<p>
  <img src="https://img.shields.io/badge/Python-3.9-blue?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/OpenCV-red?style=flat-square" alt="OpenCV" />
  <img src="https://img.shields.io/badge/TensorFlow-green?style=flat-square" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/NumPy-orange?style=flat-square" alt="NumPy" />
</p>

---

<h2>📫 Contact</h2>

<p>
  Reach out for collaboration or improvements:
  <br>
  📧 Email: <b>gantisharan6639@gmail.com</b>  
  🔗 LinkedIn: <a href="https://linkedin.com/in/sharan-ganti" target="_blank">Sharan Ganti</a>
</p>

---

<p align="center">🔹 Built for a safer tomorrow! 🔹</p>
