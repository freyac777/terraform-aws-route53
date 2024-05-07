# terraform-aws-route53
```
module "aws_route53" {
    source = "freyac777/route53/aws"
    type = "NS"
    name = "test.example.com"
}
```