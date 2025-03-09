# FoodWeOrder - A Flask-WechatApplet Food Ordering System

A WeChat integrated food ordering platform with admin dashboard, statistics, and payment processing.

## Features

- **User Authentication**
  - Member login/registration via WeChat OAuth
  - Admin panel access control
- **Food Management**
  - CRUD operations for menu items
  - Inventory tracking and sales statistics
- **Order Processing**
  - WeChat Pay integration
  - Order queue management
  - Real-time sales updates
- **Statistics & Reporting**
  - Daily sales reports
  - Member growth tracking
  - Food popularity analytics
- **Background Jobs**
  - Payment timeout handling
  - Daily stats generation
  - Queue processing

## Startup

export ops_config=local|production && python manage.py runserver

## API

The system provides RESTful APIs for:
- Member management 
- Food ordering
- Payment processing
- Address management


## License

MIT License (See LICENSE file for details)
