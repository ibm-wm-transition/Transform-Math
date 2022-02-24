# Transform-Math

## Getting Started
Following instructions will get you a copy of the specific Date transform in your webMethods.io Integration tanent.
List of Date transform available in the webMethods.io Integration are:
1. <b> Absolute : </b>This operation lets you fetch the absolute value of the given number.
2. <b> Division: </b>This operation lets you fetch the result of the division of two numbers.
3. <b> Max : </b>This operation lets you fetch the largest element from the given array.
4. <b> Min :</b> This operation lets you fetch the smallest element from the given array.
5. <b> Multiply :</b> This operation lets you multiply two or more numbers.
6. <b> Multiply List Values: </b>This operation lets you multiply all elements of the given array.
7. <b> Random:</b> This operation lets you generate a random number.
8. <b> Round Number:</b> This operation lets you round off the specified number.
9. <b> Subtract:</b> This operation lets you subtract two numbers.
10. <b> Sum: </b>This operation lets you add two or more numbers.
11. <b> Sum List Values</b> : This operation lets you fetch the sum of all elements of the given array.

### Prerequisites
1. An account in [webmethod.io](https://www.softwareag.cloud/site/product/webmethods-io-integration.html) with webMethods.io Integration access.

### Importing the recipie to your webMethods.io Integration tanent:
1. Download the specific zip file which transform you want test, from this github page.
2. Log in to your webmethod.io account then go to `webMethods.io Integration`.
3. Select `Reciepes` the click on `Import`.
![image](https://user-images.githubusercontent.com/60179170/88805095-5d798500-d1cc-11ea-97de-dec146247ecc.png)
4. Then select the downloaded file and click on `open`.
![image](https://user-images.githubusercontent.com/60179170/88919006-0933db00-d288-11ea-92c0-c06aca806803.png)
5. After that you will be able the workflow in your recipie list.<br/>
![image](https://user-images.githubusercontent.com/60179170/88919083-236db900-d288-11ea-8748-0df58c9ef64f.png)
6. Click on that workflow and then select the project name where you want to import the workflow and click on `Done`.
![image](https://user-images.githubusercontent.com/60179170/88805882-5737d880-d1cd-11ea-8414-17324e86dcd6.png)
7. After that you will see a short description about that transform along with the workflow name. Click on `Import` here.
![image](https://user-images.githubusercontent.com/60179170/88919169-48622c00-d288-11ea-9e65-ba84509c675b.png)
Yeee now you have succesfully imported the work flow.

### Run the workflow:
1. Go to that specific project where you have imported the workflow. Hover over the workflow that you have imported and click on `edit`.
![image](https://user-images.githubusercontent.com/60179170/88923555-8a42a080-d28f-11ea-996f-43eb230c7d41.png)
2. Click on the `edit` icon present in the top left corner.
![image](https://user-images.githubusercontent.com/60179170/88808530-a29fb600-d1d0-11ea-90e1-d4efeebfe853.png).
3. Now go to the workflow description and coppy the requested body. `only the JSON part`. And click `Done`. <b> If There is no request body present you can dirctly run the workflow (Step 8).</b>
![image](https://user-images.githubusercontent.com/60179170/88923677-b827e500-d28f-11ea-8349-e4d692c8e432.png)
4. Now `double click` on the start .
![image](https://user-images.githubusercontent.com/60179170/88809305-9700bf00-d1d1-11ea-91a2-235dfaf46578.png).
5. From the list click on webhook.<br/>
![image](https://user-images.githubusercontent.com/60179170/88810663-49855180-d1d3-11ea-914e-09f501278c2f.png)
6. Click `Next`.<br/>
![image](https://user-images.githubusercontent.com/60179170/88910377-05995780-d27a-11ea-99cc-b472dac0f0ef.png)
7. Now paste the coppied data in to the body and click `Next` and then `Done`.
![image](https://user-images.githubusercontent.com/60179170/88923761-dab9fe00-d28f-11ea-8565-6b267d86953b.png)
8. Now run the workflow it will give you output in the logger. Here you can see the sum result of number 1 and number 2.<br/>
![image](https://user-images.githubusercontent.com/60179170/88924135-7481ab00-d290-11ea-9d04-2c49a663c5d2.png)

### Test With other input:
1. Open the weebhook and change the data inside the body. <b> Donot change the key value and the formte of the data. ie. "num1", "num2" are key here and formate of the data is integer </b>.<br/>
![image](https://user-images.githubusercontent.com/60179170/88923937-22d92080-d290-11ea-9685-220019de4f1d.png)
2.  Now run the workflow it will give you output in the logger. 

--------
These tools are provided as-is and without warranty or support. They do not constitute part of the Software AG product suite. Users are free to use, fork and modify them, subject to the license agreement. While Software AG welcomes contributions, we cannot guarantee to include every contribution in the master project.
