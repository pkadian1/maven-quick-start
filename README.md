# maven-quick-start

- uses: mr-smithers-excellent/docker-build-push@v5
        name: Build & push Docker image in quay
        with:
          image: pkadian1/mvn-quickstart
          registry: quay.io
          dockerfile: Dockerfile
          username: pkadian1+do288
          password: ${{ secrets.QUAY }}
