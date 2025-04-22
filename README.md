# Project Zomboid Server Docker Image

### Based in [indifferentbroccoli repository](https://github.com/indifferentbroccoli/projectzomboid-server-docker)

- This repository only modify .env and ready for build and run in your docker

## Server Requirements

| Resource | Minimum | Recommended                             |
| -------- | ------- | --------------------------------------- |
| CPU      | 4 cores | 4+ cores                                |
| RAM      | 4GB     | Recommend over 8GB for stable operation |
| Storage  | 5GB     | 10GB                                    |


Clone repository:

`git clone https://github.com/Tonymartos/pz-server-docker.git`


Build with compose:

`docker compose build`


And run it:

`docker compose up -d`
