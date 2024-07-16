# mlops-project


# Step 2: Install pipenv if not already installed
pip install pipenv

# Step 3: Create a new pipenv environment
pipenv --python 3.10  # Specify your desired Python version

# Step 4: Activate the pipenv shell
pipenv shell

# Step 5: Clone the MageAI MLOps repository
git clone https://github.com/mage-ai/mlops.git
cd mlops

# Step 6: Install the required packages
pipenv install

# Step 7: Install additional dependencies
pipenv install pandas nltk matplotlib selenium tqdm seaborn


# Launch Mage and the database service (PostgreSQL):

./scripts/start.sh