## EZ Rent

### Project Team

| Image                                                                                                                      | Name              | Role              |
|----------------------------------------------------------------------------------------------------------------------------|-------------------|-------------------|
| <img src="https://avatars.githubusercontent.com/u/97714392?s=96&v=4" style="border-radius:50%" width="100" height="auto" > | Beemnet Alemayehu | Software Engineer  |
| <img src="https://avatars.githubusercontent.com/u/89666809?s=96&v=4" style="border-radius:50%" width="100" height="auto">  | Devin Eng         | Software Engineer |
| <img src="https://avatars.githubusercontent.com/u/35468353?s=96&v=4" style="border-radius:50%" width="100" height="auto">  | Hoku Tobin        | Product Owner     |
| <img src="https://avatars.githubusercontent.com/u/5220099?s=96&v=4" style="border-radius:50%" width="100" height="auto">   | Holm Smidt        | Software Engineer |
| <img src="https://avatars.githubusercontent.com/u/46771381?s=96&v=4" style="border-radius:50%" width="100" height="auto">                           | Yang Qian         | Software Engineer |


### The Problem

Renters and homeowners entering a contractual agreement will sometimes be overly cautious about entering the deal. Not only that but people who get into disputes need an immutable record to rely upon. This is especially true when it comes to students attempting to find housing.
The Solution

### The Solution
Solution is to utilize smart contracts to create a renter/rentee framework that would allow participants to enter an agreement with less uncertainty that they’re not going to get screwed over. This will also provide a single market place where landlords can post their properties and students can browse them.

### System Components and Features

<img src="./docs/concept/system-components.png">

#### Mockup Pages

- Landing Page
  - Current Market
  - Sign-up/sign-in prompt
- User home page
  - Option to create smart contract
  - Brief overview of current smart contracts
    - Who is involved with the contract, how much each monthly payments is, etc… 
  - Renter
  - Both
    - View smart contract information: Accounts for transferring currency, smart contract expiration date.
- Admin home page
  - User Profiles:
    - Account balances: to make sure no one is going to be ripped off.

#### M1 mockups

<h4 class="ui centered header">Homeowner examples</h4>

<h5 class="ui centered header">Landing page</h5>
<img src="./docs/mockups/landing.png">

<h5 class="ui centered header">Homeowner homepage</h5>
<img src="./docs/mockups/homeowner-login.png">

<h5 class="ui centered header">Homeowner Property Overview</h5>
<img src="./docs/mockups/homeowner-rentals.png">

<h5 class="ui centered header">Homeowner Contract editor/h5>
<img src="./docs/mockups/contract-editor.png">

<h5 class="ui centered header">Homeowner Contract editor</h5>
<img src="./docs/mockups/contract-editor.png">

<h4 class="ui centered header">Renter examples</h4>

<h5 class="ui centered header">Rentable listings</h5>
<img src="./docs/mockups/listings.png">

<h5 class="ui centered header">Rentable listings</h5>
<img src="./docs/mockups/contract-negotiator.png">


#### Use Cases

- Smart Contracts
  - Track payment/deposits/fees
  - Track maintenance notes
- Landlords login into update properties/profile
- Landlord smart contract creation
- Renters are able to add renters insurance?
- Students login to browse properties listed and description of those properties.

<img src="./docs/concept/component-definition.png">

#### Smart Contract Implementation

<img src="./docs/concept/smart-contract-implementation.png">

### Beyond the Basics

This would be done using smart contracts which are immutable programs that are set on the network. Smart contracts can be used to create an agreement between the renter and landlord. This means that the timing of payments will happen in perpetuity until the smart contract exists or is removed. The only way to change the smart contract is by creating a new one.
