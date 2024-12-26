<h1>Machine Learning Hydrological Forecasting</h1>

<p>This repository provides hands-on Jupyter Notebooks for building machine learning models for hydrological forecasting. The project environment is managed using Poetry to ensure consistency across platforms.</p>

<hr>

<h2>📁 Project Structure</h2>

<pre>
ml-hydrological-forecasting/
├── notebooks/              # Jupyter notebooks
│   ├── example_notebook.ipynb
├── pyproject.toml          # Poetry dependency file
├── poetry.lock             # Poetry lock file (auto-generated)
├── README.md               # Project documentation
</pre>

<hr>

<h2>🚀 How to Run the Project</h2>

<p>You can run this project by either <strong>cloning the repository</strong> or <strong>copying the folder</strong> from GitHub to your computer.</p>

<h3>🛠️ Prerequisites</h3>
<ol>
  <li><strong>Install Python</strong>:
    <ul>
      <li>Download Python (version 3.7.16 recommended) from <a href="https://www.python.org/" target="_blank">python.org</a>.</li>
      <li>Make sure to check the box to <strong>Add Python to PATH</strong> during installation (Windows users only).</li>
    </ul>
  </li>
</ol>

<hr>

<h2>🏗️ Step 1: Create a New Python Environment</h2>

<p>To isolate your project environment and ensure compatibility, follow these steps:</p>

<h3>For macOS and Linux Users</h3>
<ol>
  <li>Open a terminal.</li>
  <li>Install Python 3.7.16 if not already installed. On Linux, use:
    <pre><code>sudo apt update
sudo apt install python3.7 python3.7-venv
    </code></pre>
  </li>
  <li>Create a new virtual environment named <code>IUPWARE</code>:
    <pre><code>python3.7 -m venv IUPWARE</code></pre>
  </li>
  <li>Activate the virtual environment:
    <pre><code>source IUPWARE/bin/activate</code></pre>
  </li>
</ol>

<h3>For Windows Users</h3>
<ol>
  <li>Open a Command Prompt or PowerShell.</li>
  <li>Install Python 3.7.16 if not already installed. Use the official Python installer from <a href="https://www.python.org/" target="_blank">python.org</a>.</li>
  <li>Create a new virtual environment named <code>IUPWARE</code>:
    <pre><code>python -m venv IUPWARE</code></pre>
  </li>
  <li>Activate the virtual environment:
    <pre><code>IUPWARE\Scripts\activate</code></pre>
  </li>
</ol>

<hr>

<h2>🏗️ Step 2: Install Poetry</h2>
<ol>
  <li>Once the virtual environment is activated, install Poetry:
    <pre><code>pip install poetry</code></pre>
  </li>
  <li>Verify the installation:
    <pre><code>poetry --version</code></pre>
  </li>
</ol>

<hr>

<h2>🏗️ Step 3: Install Project Dependencies</h2>

<h3>Option 1: Clone the Repository</h3>
<ol>
  <li>Open a terminal or command prompt.</li>
  <li>Clone the repository to your computer:
    <pre><code>git clone https://github.com/yourusername/ml-hydrological-forecasting.git
cd ml-hydrological-forecasting
    </code></pre>
  </li>
</ol>

<h3>Option 2: Copy the Folder</h3>
<ol>
  <li>Download or copy the project folder from GitHub to your computer.</li>
  <li>Navigate to the copied folder in your terminal:
    <pre><code>cd /path/to/copied-folder/ml-hydrological-forecasting</code></pre>
  </li>
</ol>

<h3>Install Dependencies</h3>
<ol>
  <li>Install the dependencies listed in <code>pyproject.toml</code>:
    <pre><code>poetry install</code></pre>
  </li>
  <li>Activate the Poetry-managed environment:
    <pre><code>poetry shell</code></pre>
  </li>
</ol>

<hr>

<h2>📊 Step 4: Run Jupyter Notebooks</h2>
<ol>
  <li>Start the Jupyter Notebook server:
    <pre><code>jupyter notebook</code></pre>
  </li>
  <li>Open the notebook file (e.g., <code>example_notebook.ipynb</code>) in your browser and run the cells.</li>
</ol>

<hr>

<h2>❓ Troubleshooting</h2>
<ul>
  <li><strong>Python Version Issues</strong>: Make sure you have Python 3.7.16 installed. Check your version:
    <pre><code>python --version</code></pre>
  </li>
  <li><strong>Dependencies Not Installing</strong>: If Poetry isn’t installing the libraries, clear the Poetry cache and try again:
    <pre><code>poetry cache clear pypi --all
poetry install
    </code></pre>
  </li>
  <li><strong>Environment Not Activating</strong>: Ensure you’re in the correct directory where <code>pyproject.toml</code> is located.</li>
</ul>

<hr>

<h2>⚙️ What Does This Project Use?</h2>
<p>The environment is managed using Poetry. The dependencies are:</p>
<ul>
  <li><code>scikit-learn 1.0.2</code>: Machine learning algorithms</li>
  <li><code>numpy ^1.21.5</code>: Numerical computations</li>
  <li><code>pandas ^1.3.5</code>: Data manipulation</li>
  <li><code>matplotlib ^3.5.3</code>: Data visualization</li>
  <li><code>jupyter ^1.0.0</code>: Interactive notebooks</li>
</ul>
<p>All dependencies are listed in the <code>pyproject.toml</code> file.</p>

<hr>

<h2>📜 License</h2>
<p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>