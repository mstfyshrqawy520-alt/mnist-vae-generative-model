

<div class="container">

<h1>🧠 MNIST Variational Autoencoder (VAE)</h1>

<div class="card">
<h2>📌 Project Overview</h2>
<p>
This project implements a <span class="highlight">Variational Autoencoder (VAE)</span> using PyTorch to generate handwritten digits from the MNIST dataset.
The model learns a structured latent space representation and generates new digit images by sampling random points from a learned Gaussian distribution.
</p>
</div>

<div class="card">
<h2>🎯 Objectives</h2>
<ul>
<li>Train a Variational Autoencoder on MNIST</li>
<li>Learn a Gaussian latent distribution</li>
<li>Apply the Reparameterization Trick</li>
<li>Generate new digits from random latent vectors</li>
<li>Visualize reconstruction and sampling results</li>
</ul>
</div>

<div class="card">
<h2>🧠 Architecture</h2>
<p><span class="highlight">Encoder:</span> 784 → 400 → (μ, logσ²)</p>
<p><span class="highlight">Reparameterization:</span> z = μ + σ * ε</p>
<p><span class="highlight">Decoder:</span> latent_dim → 400 → 784</p>
</div>

<div class="card">
<h2>📉 Loss Function</h2>
<p>
Total Loss = <span class="highlight">Reconstruction Loss (BCE)</span> + 
<span class="highlight">KL Divergence</span>
</p>
<p>
KL term regularizes the latent space toward a standard normal distribution,
enabling meaningful sampling and smooth interpolation.
</p>
</div>

<div class="card">
<h2>📊 Dataset</h2>
<ul>
<li>MNIST handwritten digits</li>
<li>60,000 training samples</li>
<li>28x28 grayscale images</li>
</ul>
</div>

<div class="card">
<h2>🛠 Tech Stack</h2>
<ul>
<li>Python</li>
<li>PyTorch</li>
<li>Torchvision</li>
<li>Matplotlib</li>
<li>NumPy</li>
</ul>
</div>

<div class="card">
<h2>💡 Engineering Highlights</h2>
<ul>
<li>Modular Encoder/Decoder design</li>
<li>Custom loss decomposition</li>
<li>GPU support</li>
<li>Latent space sampling</li>
<li>Generative modeling fundamentals</li>
</ul>
</div>

<div class="card">
<h2>🚀 Future Improvements</h2>
<ul>
<li>CNN-based VAE</li>
<li>Conditional VAE</li>
<li>Beta-VAE</li>
<li>Latent space visualization</li>
<li>GAN comparison</li>
</ul>
</div>

<div class="footer">
Built with ❤️ by Mostafa El-Sharqawy
</div>

</div>
</body>
</html>
