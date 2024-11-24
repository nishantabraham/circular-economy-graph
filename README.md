# circular-economy-graph
Creating a graph database to map the circular economy so that NGOs and volunteers can effectively make a difference.

# Why this project is useful
The use and throw mindset of capitalism is causing great damage to the environment, creating enormous waste, and disproportionately affecting the marginalized sections of society. Various NGOs are chipping away at different parts of the connected problems, but need support to change people's mindset, work in a coordinated manner with other NGOs, ensure government buy-in and participation, and connecting effectively with volunteers who want to help. This needs making sense of and linking disparate data points of a complex system.
Traditional relational databases are great at handling the scale of structured and well defined tabular data but will struggle with the complexities of the undirected relationship-heavy interlinked data. I believe graph databases will thrive with such complexities.
By providing a platform with a graph-database backend, NGOs and volunteers can greatly benefit by coordinating and crowdsourcing the issues that they are individually struggling with.

# How to get started with this project

Currently, the project uses a Python, Flask and Neo4j stack, so that only open-source software is being used. Python will set up a local Flask website that the user can interact with to make changes to the graph database that is hosted in Neo4j Aura, a graph platform cloud service offered by Neo4j.

# Usage

Unzip the CE-graph file to a folder. Then:

cd CE-graph

pip install virtualenv

virtualenv venv

source venv/bin/activate

pip install -r requirements.txt

python 01_site_db_code.py


Go to the below URL in your browser:
http://localhost:50000

