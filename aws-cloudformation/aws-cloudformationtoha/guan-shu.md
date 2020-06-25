# 関数

## Ref Join Sub



```yaml
InternetGateway:
  Type: AWS::EC2::InternetGateway
  Properties:
    Tags:
    - Key: Name 
      Value: !Join ['-', [!Ref Env, 'ig']]
```

