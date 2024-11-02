# GitHub Action - Create homepage bookmark config

This GitHub Action helps to create homepage bookmark config


## Usage

Add this step in your workflow file
```yaml
-   name: Create homepage bookmark config
    id: create_homepage_bookmark_config
    uses: A-A-S-DevLab/actions-create-homepage-bookmark-config@v1.0.0
    with:
        directory: ./
        filename: config.yml
        domain_name: test.domain.com
        server_local_ip: 192.168.0.111
        service_port: 8080
        server_host: 10.7.0.1
```

## Input variables

- `directory`: Target directory
- `filename`: Target file name
- `domain_name`: Service domain name
- `server_local_ip`: Server IP in local network
- `service_port`: Service port in local network
- `server_host`: Server IP in VPN network