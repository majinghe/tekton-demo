## 文件说明



- `pipelineresource.yaml`：指定了 CI/CD 构建时的 Input（源码地址，即上述 java 的 GitHub 地址）；Output（dockerhub 地址）；
- `sa.yaml`：ServiceAccount 信息，里面关联了登陆 GitHub 以及 Dockerhub 的 Secret 信息；
- `secret-credentials.yaml`：登陆 GitHub 及 Dockerhub 时，所需要的用户名密码信息；
- `task.yaml`：task 定义信息；
- `taskrun.yaml`：taskrun 定义信息；
