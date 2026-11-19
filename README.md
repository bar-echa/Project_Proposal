Restaurant Finder
Project Description
Restaurant Finder is a React Native mobile application that helps users discover restaurants based on their location, preferred cuisine, and search keywords. By integrating with the Yelp Fusion API, the application provides real-time restaurant information, allowing users to browse available dining options and access detailed restaurant data directly from their mobile devices.

The application enables users to search for restaurants by city, cuisine, or restaurant name, view a list of matching results, and explore detailed information about each restaurant, including ratings, photos, addresses, phone numbers, pricing, and business hours when available. The project is designed to provide a clean, responsive, and user-friendly experience while demonstrating modern mobile development practices.

Project Overview
Restaurant Finder is developed using React Native and Expo and focuses on integrating live API data rather than using a local database. The application demonstrates key concepts learned throughout the course, including API integration, asynchronous programming, navigation between screens, reusable components, responsive layouts, and state management using React Hooks.

Features
Search restaurants by name, cuisine, or location.

Browse restaurant listings retrieved from the Yelp Fusion API.

View restaurant ratings and categories.

Display restaurant photos and contact information.

Access detailed restaurant information.

Responsive mobile interface using Flexbox.

Navigation between multiple screens.

Loading indicators and error handling.

Reusable React Native components.

Screens
1. Home and Search Screen
Users can enter a restaurant name, cuisine type, or location to begin their search.

2. Restaurant Results Screen
Displays restaurant search results using FlatList with restaurant images, ratings, categories, and addresses.

3. Restaurant Details Screen
Provides detailed information about a selected restaurant, including photos, ratings, address, phone number, price range, and business hours when available.

Technologies Used
React Native

Expo

JavaScript

Axios

Yelp Fusion API

React Navigation

React Hooks (useState, useEffect)

FlatList

Expo Vector Icons

Flexbox and React Native StyleSheet

API Integration
This project uses the Yelp Fusion API to retrieve restaurant information.

API Endpoints:

Business Search Endpoint: /v3/businesses/search

Business Details Endpoint: /v3/businesses/

API Documentation: https://docs.developer.yelp.com/ 

Axios and async/await will be used to retrieve restaurant information from the API.

Developer Information
Developer Name: Barecha Umeta

Team Name: Solo Developer

Project Type: Individual Project

Course: SODV2205-01 – Mobile Application Development with React Native I

Institution: Bow Valley College

Project Objectives
Develop a functional restaurant discovery mobile application.

Integrate a live third-party API using Axios.

Implement at least three interactive application screens.

Demonstrate React Hooks and state management.

Use React Navigation for screen navigation.

Display API results using FlatList.

Create reusable components.

Design a responsive interface using Flexbox.

Handle loading states and API errors.
