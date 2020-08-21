# RAILS TUTORIAL

Learning to code rails application with the complete ruby on rails developer course from Udemy

## The Front-end: Destroying (deleting) articles

REST - Representation State Transfer - mapping HTTP verbs (get, post, put/patch, delete) to CRUD actions

resources provides REST-ful routes to Rails resources.

## Code Refactoring

DRY code - Don't repeat yourself

- re-factoring
- extract away redundancies in code

## Resource

- Users - create users table and model - add validations
  _ username must be present and unique, min 3 max 25
  _ email address must be present and unique, max 105 \* email must be valid email format, check with email regex

## Associations

- One-to-many
  between users and articles

## REST for users

Authentication

- Login using secure password

Restriction of actions

- Based on logged in/logged out state

Security

- Admin user functionality and access level

## Show User Info

Display username in articles index and show

## The before_save method

Change an object's state before saving to database
 <before_save { self.email = email.downcase }>

## Intro and add authentication

Add has_secure_password to users using bcrypt 

## User Sign Up Form

Build new user sign up form

## Create new users back-end

Handle form submission for users sign up

## Edit existing users

Add edit functionality to existing user information