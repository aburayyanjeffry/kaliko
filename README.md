<img src="img/imgbin_calico-cat.png" width=30% height=30%>
<!--- https://imgbin.com/png/teExm7p4/calico-cat-%E9%A6%99%E7%AE%B1%E5%BA%A7%E3%82%8A-illustrator-png --->

# kaliko
`kaliko` is a DIY trial CKA thats run on your AWS account. This is a free means to practice and exercise before going to the real CKA exam. Please take note that the look and feel of kaliko and CKA is not the same. kaliko only test on the K8s knowledge according to the subjects thats going to be ask in CKA as pointed out by CNCF. 

Event though kaliko is free, your AWS account is not. Monitor your usage so that you don't go beyound the free range. 

## Prerequisite
1. AWS Free tier account


## Provision the node
Use the `EC2 Instances provisioning` and `Installing the container runtime` of this [blog](https://www.endpointdev.com/blog/2022/10/kubernetes-from-the-ground-up-with-aws-ec2/) to provision the controlplane and the worker node

## The exam.
Login to control plane and to the following questions and execute the following command to prepare the exam environment:
```
mkdir /tmp/kaliko
```

### Question 1
Install kubernetes 1.23 . Once done execute the following command to submit your answer
```
kubectl get nodes > /tmp/kaliko/question01
```


