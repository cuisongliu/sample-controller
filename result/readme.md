1. 配置相关信息 进入 artifacts/example 目录 执行 kubectl create -f crd.yaml
2. 进入代码根目录 执行go build -o controller.exe
3. 执行 controller.exe -kubeconfig=C:\\Users\\cuisongliu\\.kube\\config