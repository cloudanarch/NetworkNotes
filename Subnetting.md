#Subnetting

"Breaking down large network into smaller network, or subnets" 
Makes Networks more manageable. 

- Having too many IPs can create excess traffic
- Too hard to pinpoint
- If you're in multiple locations it creates a problem

Breaking Down into Subnets makes it better.

- Change default subnet mask by "borrowing" host bits to create subnets. 

## Subnet formula

#### 2^n - 2
##### n = number of bits

## Seven Second Subnetting

[Professor Messer](https://hooktube.com/watch?v=ZxAwQB8TZsM)

- /8 /16 /24 CIDR notations generally easy to calculate.

- Uses two tables. Memorize the tables and write down at beginning of exam. 

#### Step 1 : Convert IP Address AND Subnet Mask to Decimal Format.

- Example : 165.245.12.88/24

    > Find Mask decimal Address 

        > IP already in decimal format.
        
        > /24 is 255, 3rd Column :

            > 255.255.255.0
        
    
        > Address : 165. 245.12.88

        > Mask : 255.255.255.0

#### Step 2 : Calculate Network Address 

- If the mask is 255, bring down the address. If mask is 0, use the 0.

    > Find Network Address:

        > Bring down address and 0s. 

    > Network Address : 

        > 165.245.12.0

#### Step 3 : Find the Broadcast Address

- If the mask is 255, bring down the address. If mask is 0, use 255

    > Broadcast Address

        > 165.245.12.255

#### Step 4 : Find First and Last useable IP addres.

    > First IP is network address + 1

        > 165.245.12.1

    > Last IP is network address - 1

         > 165.245.12.254
         
### Creating Minimum Subnets

- Example 1: 

    >  If you need to create at least six subnets, how many bits should you use for subnetting?

        > The number of subnets that can be created is the number of bits used as the exponent to the number 2. So here, 2 raised to the 5th power is 32 subnets. 2 raised to the 6th power is 64. 2 raised to the 4th power is 16, and 2 raised to the 3rd power is 8.

### Other Examples 

- Example 

    > You are designing a small office/home office (SOHO) network, and you wish to have four subnets, while maximizing the number of hosts per subnet. The network you need to subnet is 192.168.5.0/24. Which of the following is one of the four subnets you should create? 

       > Four subnets are supported with two borrowed bits, based on the formula: number of subnets = 2^s, where s is the number of borrowed bits (that is, 2^2 = 4). Since a design requirement stated that the number of hosts per subnet be maximized, you would not want to use more borrowed bits than necessary. Therefore, you should choose a 26-bit subnet mask (that is, 255.255.255.192). The block size is 64 (that is, 256 – 192 = 64). Therefore, the subnets created by subnetting the 192.168.5.0/24 network with a 26-bit subnet mask are: 