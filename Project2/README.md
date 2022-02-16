![vpc](https://user-images.githubusercontent.com/77698986/154193632-e76a7123-f0ad-4aff-8046-4e0f0a888d53.png)
Went to aws VPC page and selected your VPC and made a new VPC, then named it SYED-VPC and choose 24 for the IP address.
![subnet](https://user-images.githubusercontent.com/77698986/154193879-3ce48e8d-fbfd-4fb9-bed7-6d17eb0f8cf9.png)
Went to the side bar and clicked subnet then chose the SYED-VPC for the VPC ID, and then named it SYED-Subnet, and choose 28 for the 
IPV4
![internetgatewayTURNIN](https://user-images.githubusercontent.com/77698986/154194011-4decea49-8dcc-46d6-8e47-c92981e24650.png)
Made the internet gateway, named it SYED-gw and then associalted it with the SYED-VPC. Made sure it was active.  
![routetable](https://user-images.githubusercontent.com/77698986/154194133-138dcda4-4182-4462-bd28-0e4f3419d934.png)
Made a route table named it SYED-routetable, and assoicated it with the SYED-VPC
![2022-02-15 (5)](https://user-images.githubusercontent.com/77698986/154195107-9a80302f-c889-4ff3-ab43-d9a829584942.png)
Made the security group added the schools and my own Ip ADDRESS, and gave it those inbounds.

PART 2
2. Go to the instance page and select launch instance, selected the UBUNTU server 20.04, t2m,micro, configured the instance 
details, added a new volume, added new tags, added exesting security group.
3. No the public ip address was not auto assigned, had to go to Elastic IPs to get a new one.
4. Gives you an option to choose from exesting one or could also add one with new rules.
5. Once on the tag page gives you an option to enter the which type of tag name in this case and the discription.
6. You can associate with adding your IP address in the security and then they would be connected to the instance onece
   you choose which one you want.
7. Go to the Elastic IPs in the left bar and allocate elastic IP address then choose name it, once done connect with your new instance
8. ![2022-02-15](https://user-images.githubusercontent.com/77698986/154195432-2f142956-bb02-4662-8221-cd7ba0522843.png)
9. hostnamectl set-hostname SYED-AMI --static
10. ![2022-02-15 (2)](https://user-images.githubusercontent.com/77698986/154195618-3310222a-a1aa-4193-8b80-4b4b9840dcee.png)
