- VPC_A
    - 10.245.0.0/16
    - US East (Ohio)us-east-2
- VPC_B
    - 10.246.0.0/16
    - US East (Ohio)us-east-2
- VPC_C
    - 10.247.0.0/16
    - US East (Ohio)us-east-2
- VPC_D
    - 10.248.0.0/16
    - US West (Oregon)us-west-2
- VPC_E_AWS_VPN
    - 10.249.0.0/16
    - US West (Oregon)us-west-2
    - create CGW, VPN connection manually
    - Automated: Route tables, SGs, VGW
- VPC_F_OnPrem
    - 10.250.0.0/16
    - US West (Oregon)us-west-2
    - configure ipsec.conf, ipsec.secrets, /etc/sysctl.conf
    - start ipsec process
    - configure SG to allow traffic from VGW
    - Automated: route tables, SGs for internal VPN traffic, source/destination checks
