# GitHub Actions CI/CD

## AWS CloudFormation

## Dockerfile
- Dockerイメージビルド
    ```
    cd github-actions-django-ecs
    docker build -t dockerimage .
    docker images
    ```
-Dockerコンテナ起動のコマンド
    ```
    docker run --rm -p 8080:8080 djangoimage
    ```

## Docker Compose
- 起動
    ```
    docker-compose up -d
    ```
- 停止
    ```
    docker-compose down
    ```