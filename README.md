# My Django Market Website

●	A web application of a shopping website that allows users to buy and sell items, update and delete their own items and contact with the item’s sellers

## Prerequisites

- Docker installed on your machine

## Getting Started

### Using Docker

1. Pull the image from Docker Hub:

    ```sh
    docker pull esadsen/django-marketproject:marketlatest
    ```

2. Run the Docker container:

    ```sh
    docker run -p 8000:8000 esadsen/django-marketproject:marketlatest
    ```

3. Open your browser and navigate to [http://localhost:8000](http://localhost:8000)

### Using Docker Compose

If you prefer to use Docker Compose, here is how you can do it:

1. Clone the repository:

    ```sh
    git clone https://github.com/esadsen/django-MarketProject.git
    cd django-MarketProject
    ```

2. Run the services:

    ```sh
    docker-compose up
    ```

3. Open your browser and navigate to [http://localhost:8000](http://localhost:8000)


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
