# Rewardful
aka *Reviewflow*
## Simple One Line Definition
### Current
An online review platform that allows businesses to reward or resolve customer reviews before they're posted live.

### Proposed
- An online communication platform that allows businesses to engage with customer reviews before they're posted live.
- An online review platform that allows businesses to engage with customer reviews before they're posted live.
- Reviews directly to the local business.
- A software platform that allows local business reviews to reach the owner first
 * Shun: this is more of a feature, not global definition
- An online platform designed to enhance the relationship between businesses and their customers after the transaction.
 * An online platform to enhance the relationship between businesses and their customers after a visit using reviews.

### Previous
- A online reviews and rewards platform designed to enhance the post-transactional relationship between businesses and their customers.
- An online platform to enhance the relationship between businesses and their customers after a visit using reviews.

## Initial Problems
Problems that this product is trying to solve.

1. There is little to no engagement between the business and the reviewer once a review is posted
2. Businesses have no opportunity to rectify any negative reviews, which can ultimately sever their ratings
3. It is difficult for many businesses to have more of their customers to write reviews
4. Too many 4.5 star rated businesses can make it harder for businesses stand out
5. Many reviews provide little to no value ("The restaurant was busy" Okay, what time and day was it busy so I can avoid going when it's busy???)

1. Submitting a negative review to the public before a owner can resolve it.
2. Increase the number of positive customers reviews 
 - Users currently are more engaged to write a review for a negative experience than a positive
3. Increase the quality of customer reviews 
 - *"Tried the Avocado Bacon Beast Burger. My favorite!"* vs *"great food great service"*
4. Allows businesses to engage with customers after the transaction
 - Before: Advertisements and promotions
 - During: Transaction
 - **After: Thanking, rewarding, resolving**

## What businesses want (unverified)
1. Businesses want more reviews
2. Businesses want more customers (both new and returning)
3. Businesses want more control over online reviews
4. Businesses want trustworthy reviews (no anonymous reviews)
5. Businesses want reviewers to write high quality reviews

## What consumers want (unverified)
1. Consumers want to know where to get great quality products and services
2. Consumers want to know how other people's experiences were with a business
3. Consumers want to receive promotions and special offers
4. Consumers want to have their voices heard
5. Most consumers don't have the time or interest to write reviews


## Pain points
Situations that can create friction or decrease the user experience.
### Current
#### For Merchants

1. How to remove negative reviews on Yelp
 - Owner must be aware of the negative review(s)
 - Owner must directly contact the Yelper and ask them to change their rating
 - Even if owner receives more recent positive reviews, Yelp will *still* show older negative reviews
2. Fake reviews
3. Consumers threatening to write a negative review

#### For Reviewers

1. Why should I bother writing a review?
 - Takes too much time
 - "I'm not a good writer"
 - Forgot
2. Businesses writing fake reviews
 
### For Development
#### For Merchants

1. Spammy reviews
 - How to decipher fake vs authentic customer reviews
  - **"Check in"** to the restaurant (Problem: extra step for Reviewer)
  - **Take a picture** of your visit (Problem: extra step for Reviewer; fake pictures)
  - **Receipt code** (Problem: extra step for Reviewer; majority of customers throw away receipts)
 - 'Merchant' wants to know if reviews are legitimate
2. How to deliver a reward
 - App sends a notification with a link to the merchant's reward/offer
 - Systematically (i.e. using Yelp platform)
  - + Piggyback off of Yelp
  - - Difficult to set up rules
 - Attach a file (i.e. PDF)
  - + Easy to program
  - - Not universal
  - - No quality control 
3. Crowd control: How do businesses keep up with a surge of review submissions?
 - Set pending period
 - Extra benefit: Allows business to send a notification to the customer on a new day
4. Crowd control: How to prevent reviewers from setting expectations that every business will reward you for a review 

#### For Reviewers

1. How to keep users engaged using Rewardful?
 - Receive a notification when a business engages or rewards you for your review
2. What happens if a business is not listed on Rewardful?
3. How to handle repeat visits
 - + "Check in" to your original review of the business (?)
 - - How to prevent users from spamming "Check ins"
4. Signing up for *another* account
 - Sign in with your Yelp account

### Proposals

## Features

### Current
1. Reviews post to the user's platform of choice.
2. Pending period between review submission and review post.
3. Resolution opportunity for merchants on pending reviews.

### Proposals
1. Reviewers can receive rewards (or a resolution) for their business review.
2. Engagement Score
 - Stand out from the rest of the 4.5 star reviews with a Customer Enagagement Score
 - Engage positive reviews by thanking or rewarding them
 - Engage negative reviews by providing a fix, resolution, or apology
 - The more reviews a business engages with, the higher the business's Engagement score
 - For example: Receive 20 reviews. Thanking, rewarding or resolving 19 of them will give the business an engagement score of 95%.


## Live
You can find the app for [merchants here](http://biz-rewardful.jastcode.com) and [reviewers here](http://rewardful.jastcode.com)

## Why
[fill after one line definition is established...]
- Continue the B2C relationship after the transaction
- 'Merchants' want feedback, endorsements, and the ability to provide engaging customer service after the visit or transaction.
- 'Reviewers' like coupons, direct conversation, rewards/recognition, notifications.
- A software platform that allows local business to recognize, reward, and/or rectify a customer review

### Current
[select]
### Proposals
- ONE LINE: A software platform that allows local business reviews to reach the owner first.
 - WHY: If the owner gets the ability to see the review before it is posted to the public there might be a window of resolution or clarity between the owner and reviewer.

## Concepts
### Review Actions for Merchant
These are actions a Merchant can take upon a pending review.
#### Ignore/Expired
Skipped or not read.
#### Read
Only read.
#### Thank You
Default thank you with custom option.
#### Reply
Open a conversation about reward.
#### Reward
Attach a coupon or comp.
#### Challenge
Flag a review for spam or as inappropriate

### Review Actions for Reviewer
These are actions that a Reviewer can do when writing a review
#### Rate 1-5 Stars
Choose a rating based on your overall experience with the business
#### Comment
Write about your experience

## User types
### Reviewers
- Lead
- Alpha (feedback on concepts)
- Beta (feedback on product itself)
- User (writing reviews on product)
 - User: Regular
 - User: Power/Elite (XX reviews a YY) 

### Merchants
- Lead
- Alpha (feedback on concepts)
- Beta (feedback on product itself)
- Merchant (rece reviews on product)
 - Merchant: Regular
 - Merchant: Power/Elite (High engagement rate) 

## Todo
Things we need to do.

### Adam
- [x] Put up a landing page.
- [ ] Create Authentication System for Merchant.
- [ ] Create Authentication System for Reviewer.

### Shun
- [ ] PRIORITY
 1. [ ] Complete Merchant lead list table.
  [Lead List](biz/sales/our-first-merchants/merchant-list.md)
 2. [ ] Complete Reviewers lead list table.
  [Lead List](biz/sales/our-first-reviewers/lead-list-Yelp-reviews.md)
 3. [ ] Add 10 products to Market Landscape.
 [Market Landscape](biz/market-landscape/general.md)
- [ ] OTHER
 - [ ] Import all of your diary notes into repo.
 - [ ] Create 500 hundred words about the project.
 - [ ] Create Script: Lead Reviewers
 - [ ] Create Script: Lead Merchants
 - [ ] Create Script: Alpha Reviewers
 - [ ] Create Script: Alpha Merchants
 
## Milestones
- Reach out to 5 local Yelp users
- Reach out to 5 local businesses
- Meetup with 5 Lead Reviewers
- Meetup with 5 Lead Merchants
- Front-end landing page for Reviewflow signups
 
## More Sections
[User Flow](user-flow.md)
