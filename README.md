# React with Docker
Create a clean project with React using docker and docker-compose.

## Pre requirements
- Docker (version `23.0.0` or later)
- Docker-compose (version `1.29.2` or later)

## How to start
1. Clone this project
  ```
  git clone https://github.com/victorlobo92/react-docker.git
  ```
2. Access the project folder:
  ```
  cd react-docker
  ```
3. Execute the setup env script (this will set your `.env` file with the necessary environment variables):
  ```
  source ./setup-env.sh
  ```
4. Start the application:
  ```
  docker-compose up
  ```

The setup will create a new react project inside reactapp folder.

After that, you can remove the `git remote` and add your own:

```
rm -rf .git && \
git init && \
git remote add origin git@github.com:your-git-user/your-git-repository
```

You are good to go! Awesome coding!