# Magento 1 Vagrant
A very basic Magento 1 vagrant box.

## Usage

Ensure all web files are within httpdocs:

- bootstrap.sh
- Vagrantfile
- /httpdocs/ {{ web files in here }}
- README.md

**Site URL:** http://127.0.0.1:8080/

- **MySQL Host:** 127.0.0.1
- **MySQL Username:** magentouser
- **MySQL Password:** password
- **MySQL Database:** magento (defined in bootstrap.sh)

- **SSH Host:** 127.0.0.1
- **SSH User:** vagrant
- **SSH Password:** vagrant
- **SSH Port:** 2222

## Troubleshooting

If you have SSH connection issues ensure the 

`$ vi ~/.ssh/known_hosts`

Go to the line with `127.0.0.1:8080` on it, then did command `dd` to delete that line. `:x` to Save.
