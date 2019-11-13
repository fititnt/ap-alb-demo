# ap-alb-demo

See <https://github.com/fititnt/ap-application-load-balancer>

## ASCIInema demo
> @TODO: visual demonstration with <https://asciinema.org> (fititnt, 2019-11-11 20:56 BRT)

## How to download this ap-alb-demo to your machine

```bash
git clone https://github.com/fititnt/ap-alb-demo.git .

# This will download https://github.com/fititnt/https://github.com/fititnt/ap-application-load-balancer
# on roles/ap-application-load-balancer
ansible-galaxy install -r requirements.yml --roles-path roles/
```

> TIP: on [requirements.yml](requirements.yml) have extra information.

## How to customize and use

```bash
# Edit to your hosts files. The default values where used on Etica.AI test servers
# You can also create a new one and change `-i hosts`
vim hosts

# This will run the playbooks
ansible-playbook -i hosts main.yml
```

### Variables used by apps-server and db-server

### Variables read only by apps_servers
### Variables read only by db_servers
- apps-server
  

## License
[![Public Domain](https://i.creativecommons.org/p/zero/1.0/88x31.png)](UNLICENSE)

To the extent possible under law, [Etica.AI](https://etica.ai/) has waived all
copyright and related or neighboring rights to this work to
[Public Domain](UNLICENSE).
