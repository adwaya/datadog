# ![DataDog](https://imgix.datadoghq.com/img/about/presskit/logo-h/logo_horizontal_purple.png)

All about DataDog



## Installing DataDog on Docker

- Installing on top of Docker

```
env DOCKER_CONTENT_TRUST=1 docker run -d --name dd-agent -v /var/run/docker.sock:/var/run/docker.sock:ro -v /proc/:/host/proc/:ro -v /sys/fs/cgroup/:/host/sys/fs/cgroup:ro -e DD_API_KEY=517b61076c2ea5fa8ba110e9461b59f9 -e DD_SITE="datadoghq.eu" datadog/agent:7
```
