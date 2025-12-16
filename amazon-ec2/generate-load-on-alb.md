# Command to generate load on the ALB

***replace with your alb dns name***
```for i in {1..200}; do curl http://ALB1-343069959.us-east-1.elb.amazonaws.com & done; wait```
