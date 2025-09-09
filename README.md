# ruby-hello-world

#### deploy from cpd-cli

```
 cpd-cli manage create-template-application --cpd_instance_ns  
      --app_name="ruby-hello-world"
      --app_proxy_config_yaml="ruby-hello-world.conf.yaml"
      --app_template=https://raw.githubusercontent.com/shixuguang/ruby-hello-world/refs/heads/main/application-template-stibuild.json
      --cpu: 100m
      --cpu_limit: 200m
      --memory: 100Mi
      --memory_limit: 200Mi 
```