# Block graph

- Open your terminal and clone this repository

  First make sure you have a ssh key if you dont have go to my dotfiles repository and follow the instructions

  ```
  git clone git@github.com:ayushkpai/block-graph.git
  ```

- Next install python and add dependencies

  Also documented in dotfiles

  ```
  uv add python-dotenv
  uv add openpyxl
  ```

- Create .env
  
  ```
  echo TRANSACTIONS_FILE=transactions.xlsx >> .env
  ```

- To run the project

  ```
  uv run Code.py
  ```
