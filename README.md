# example-system
List of service.yaml files for demonstrate how it works

![system image](https://miro.medium.com/max/1400/0*bqCEfzwZJowivElX.png)


## Push all services in one command

```
for filename in ./services/*.yaml; do
  INVENTARIUM_TOKEN=<org-token> inventarium push $filename
done
```

## License

[MIT License](https://github.com/inventarium-org/example-system/blob/master/LICENSE)
