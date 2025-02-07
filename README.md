# trino docker compose
This project aims to provide a simple and efficient development and testing environment for developers and anyone interested in exploring Trino.

The setup includes:

- **MinIO Catalog:** Pre-configured to use the Hive Metastore connector. MinIO serves as an S3-compatible object storage, enabling you to query bucket-stored data as traditional tables.  
- **Faker Catalog:** Generates realistic synthetic data for testing queries and application functionality without relying on external datasets.
## Credits
This project is built on top of two existing repositories, modified and updated for a modern Trino experience.  
Instead of forking the original projects, I made significant modifications, removing certain functionalities and adding custom features.
</br>
**Original Repositories:**  

- [trino-hive-docker](https://github.com/sensei23/trino-hive-docker/tree/main)

- [trino-dbt](https://github.com/starburstdata/dbt-trino/tree/master)

Special thanks to the contributors of both projects!

## Getting Started
To get started, follow these simple steps:

1. Ensure that Docker is installed on your machine.
2. Navigate to the project directory in your terminal or command prompt.
3. Run the following command:
```bash
   docker-compose up
```
thats it!

### Contribute & Support
If you like the project, please help us stay relevant by contributing and sharing your feedback.
