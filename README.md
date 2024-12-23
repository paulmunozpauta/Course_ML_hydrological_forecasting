# ML_hydrological_forecasting
A hands-on course on ML hydrological forecasting
<h1>Hydrological Forecasting with Machine Learning</h1>

<p>This repository provides Jupyter Notebooks and a Poetry-managed Python environment for developing machine learning models for hydrological forecasting.</p>

<hr>

<h2>Setting Up the Environment</h2>

<p>To replicate the environment and run the notebooks, follow these steps:</p>

<h3>Step 1: Clone the Repository</h3>
<p>First, clone the repository to your local machine:</p>
<pre>
<code>
git clone https://github.com/yourusername/your-repository.git
cd your-repository
</code>
</pre>

<h3>Step 2: Install Poetry</h3>
<p>Install Poetry if it is not already installed:</p>
<pre>
<code>
pip install poetry
</code>
</pre>
<p>Verify the installation:</p>
<pre>
<code>
poetry --version
</code>
</pre>

<h3>Step 3: Create and Activate the Environment</h3>
<p>Use Poetry to install the dependencies and set up the environment:</p>
<pre>
<code>
poetry install
</code>
</pre>
<p>Activate the environment:</p>
<pre>
<code>
poetry shell
</code>
</pre>

<h3>Step 4: Run Jupyter Notebook</h3>
<p>Once the environment is set up, start the Jupyter Notebook server:</p>
<pre>
<code>
jupyter notebook
</code>
</pre>
<p>Open the notebook in your browser and execute the cells.</p>

<hr>

<h2>Troubleshooting</h2>
<ul>
  <li>Ensure your Python version matches the requirement in <code>pyproject.toml</code> (e.g., Python >=3.7, <3.9).</li>
  <li>If <code>poetry install</code> fails, ensure your system has internet access to download dependencies.</li>
  <li>Use the following command to verify the installed version of <code>scikit-learn</code>:
    <pre>
    <code>
    python -m pip show scikit-learn
    </code>
    </pre>
    The expected version is <code>1.0.2</code>.
  </li>
</ul>

<hr>

<h2>Project Structure</h2>
<ul>
  <li><code>notebooks/</code>: Contains the Jupyter Notebooks.</li>
  <li><code>pyproject.toml</code>: Lists project dependencies.</li>
  <li><code>poetry.lock</code>: Locks dependency versions for reproducibility.</li>
</ul>

<hr>

<h2>License</h2>
<p>This project is licensed under the MIT License.</p>