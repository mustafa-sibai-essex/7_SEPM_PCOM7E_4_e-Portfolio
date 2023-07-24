<link rel="stylesheet" href="../../style.css">

## Question
OVERVIEW <br><br>
Instructions: Read the Behaviour Driven Development (2020) pages and then use the Gherkin language to create a Gherkin sequence that addresses ONE of the following examples: <br><br>
Using a new coffee making machine.<br>
Interfacing with a new SatNav system.<br>
Using a computer running the Linux operating system.<br>
Getting familiar with a new vehicle.<br>
Creating a batch or shell script.<br>
Your response should consist of at least three scenarios describing different roles such as administrator, user, driver and so on.<br>


## Answer:

Example: Getting Familiar with a New Vehicle

<div class="container">  
    <div class="text-section"> 
<p>
Feature: Vehicle Introduction<br>
As a new driver<br>
I want to get familiar with the features of my new vehicle<br>
So that I can use it safely and efficiently<br>
<br>
Scenario: Basic Controls Introduction<br>
Given I am a new driver<br>
When I sit in the driver's seat<br>
Then I should be shown the location and function of important controls<br>
And I should be informed about the purpose of the brake, accelerator, and clutch pedals<br>
And I should be shown how to adjust the mirrors for optimal visibility<br>
<br>
Scenario: Infotainment System Introduction<br>
Given I am a new driver<br>
When I start the vehicle<br>
Then I should be guided through the setup of the infotainment system<br>
And I should be shown how to connect my smartphone via Bluetooth<br>
And I should be informed about the navigation system and how to use it to find directions<br>
<br>
Scenario: Safety Features Explanation<br>
Given I am a new driver<br>
When I am introduced to the vehicle's safety features<br>
Then I should be informed about the functioning of airbags and seatbelts<br>
And I should be shown how to engage and disengage the parking brake<br>
And I should be given a demonstration of how the collision avoidance system works<br>
<br>
These scenarios address the different aspects of getting familiar with a new vehicle, starting from the basic controls and driving features, to the infotainment system, and finally, an introduction to the safety features.
</p> 
    </div>  
    <div class="image-section">    
        <img src="static/vehicle.jpg" width="275"/>
    </div> 
</div>

<div class="container">  
    <div class="text-section"> 
<p>
More examples:<br>
<br>
Feature: User Login<br>
As a registered user<br>
I want to log in to the website<br>
So that I can access my account<br>
<br>
Scenario: Successful login<br>
Given I am on the login page<br>
When I enter my valid username "foo123" and password "bar123"<br>
And I click the login button<br>
Then I should be redirected to the dashboard page<br>
And I should see a welcome message "Welcome, foo123!"<br>

<br>
Feature: Shopping Cart<br>
As a customer<br>
I want to add items to my shopping cart<br>
So that I can purchase them later<br>
<br>
Scenario: Add item to the shopping cart<br>
Given I am on the product page<br>
When I click on the "Add to Cart" button for "Product A"<br>
Then the item "Product A" should be added to my shopping cart<br>
And the cart icon should display "1" item<br>

<br>
Feature: Account Settings<br>
As a registered user<br>
I want to update my account settings<br>
So that I can keep my information up to date<br>
<br>
Scenario: Change password<br>
Given I am logged in to my account<br>
When I navigate to the account settings page<br>
And I click on the "Change Password" section<br>
And I enter my current password "oldPassword123" and new password "newPassword456"<br>
And I click the "Save Changes" button<br>
Then I should see a success message "Password updated successfully"<br>
<br>

Feature: Search Functionality<br>
As a website visitor<br>
I want to search for products<br>
So that I can find specific items quickly<br>
<br>
Scenario: Search for a product<br>
Given I am on the homepage<br>
When I enter "game console" into the search bar<br>
And I click the search button<br>
Then I should see a list of products related to "game consoles"<br>
And the list should contain at least one item with the word "game console" in its name or description<br>
</p> 
    </div>  
    <div class="image-section">    
        <img src="static/shopping.jpg" width="275"/>
    </div> 
</div>