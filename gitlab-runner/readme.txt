docker run -d --name gitlab-runner --restart always \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v /srv/docker/gitlab-runner/config:/etc/gitlab-runner \
  --net=host \
  --privileged \
  gitlab/gitlab-runner:latest


  reference
  https://gitlab.com/gitlab-org/gitlab-ci-multi-runner/blob/master/docs/install/linux-repository.md