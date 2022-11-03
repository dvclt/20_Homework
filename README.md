# Module 20 Challenge

1. Use the `setAccounts` function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

   > ```text
   > Dummy account1 address: 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb
   > Dummy account2 address: 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0
   > ```

   ![image1](./Execution_Results/01_setAccounts.PNG)

2. Test the deposit functionality. After each transaction, use the `contractBalance` function to verify that the funds were added to your contract:

   - Transaction 1: Send 1 ether as wei.
     ![image2_1](./Execution_Results/02_01_send%201%20ether%20as%20wei.PNG)
   - Transaction 2: Send 10 ether as wei.
     ![image2_2](./Execution_Results/02_01_send%2010%20ether%20as%20wei.PNG)
   - Transaction 3: Send 5 ether.
     ![image2_3](./Execution_Results/02_03_send%205%20ether.PNG)

3. Test the withdrawal functionality:

   - withdrawing 5 ether into `accountOne`.
     ![image3_1](./Execution_Results/03_01_withdraw%205%20into%20accountOne.PNG)
   - withdrawing 10 ether into `accountTwo`.
     ![image3_2](./Execution_Results/03_02_withdraw%205%20into%20accountTwo.PNG)

After each transaction, use the `contractBalance` function to verify that the funds were withdrawn from your contract. Also, use the `lastToWithdraw` and `lastWithdrawAmount` functions to verify that the address and amount were correct.
