<div align=center>
  <h1>🌿 Plant Village Classification</h1>
  <p><strong>Author:</strong> <a href="https://www.kaggle.com/subarnasaikia" target="blank">Subarna Saikia</a></p>
  <p>Dataset: 
    <a href="https://www.kaggle.com/datasets/emmarex/plantdisease" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="subarnasaikia" height="30" width="40" /></a>
    <a href="https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="subarnasaikia" height="30" width="40" /></a>
  </p>
</div>
<hr/>

<p>This project classifies plant leaf images into 15 distinct categories using a deep learning model built on <strong>MobileNetV2</strong>. The dataset is taken from the <em>PlantVillage</em> collection.</p>

<h2>🚀 Features</h2>
<ul>
  <li>Uses <strong>Transfer Learning</strong> with MobileNetV2</li>
  <li>Data Augmentation for better generalization</li>
  <li>Early Stopping, Model Checkpointing & Learning Rate Scheduling</li>
  <li>Achieves over <strong>93% validation accuracy</strong></li>
</ul>

<h2>🧠 Classes</h2>
<p>15 classes including bacterial spot, early/late blight, mold, viruses, and healthy leaves across pepper, potato, and tomato.</p>

<h2>🛠️ Model Architecture</h2>
<ul>
  <li>Base: MobileNetV2 (frozen)</li>
  <li>Custom Dense layers: 1024 → 768 → 512 → Softmax(15)</li>
</ul>

<h2>📈 Training Highlights</h2>
<ul>
  <li>Epochs: 25</li>
  <li>Accuracy: ~95% (training), ~93% (validation)</li>
</ul>

<h2>🔗 Notebook</h2>
<p>Check the full code in <a href="main.ipynb"><code>main.ipynb</code></a>.</p>

<h2>📦 Requirements</h2>
<pre>
TensorFlow
NumPy
OpenCV
Matplotlib
</pre>

<h2>📜 License</h2>
<p>MIT License</p>

