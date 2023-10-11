### xpaste_practicum playbook

### Project for the Slurm ansible learning course

#### 📦 Requirements:
- CentOS 7
- <a href="https://www.python.org/downloads/">Python 3</a>
- <a href="https://pypi.org/project/Jinja2/">Jinja 2</a>

#### 🧑‍🏭 Included roles:
 - Nginx install
 - PostgreSQL install 
 - Dependencies install

#### ▶️ Usage:
1. Put your vars in the ``` ~/group_vars/all.yml ```
2. Run the playbook using ``` ansible-playbook -i hosts.yml slurm-playbook.yml ```




