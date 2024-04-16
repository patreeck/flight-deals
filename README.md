# Flight Price Tracker

Flight Price Tracker is a tool that helps monitor flight prices between a specified origin city and various destinations. It uses live flight data to identify and notify users of low-price flight opportunities via SMS.

## Features

- Fetches destination data including city names and corresponding airport codes.
- Utilizes a flight search API to check flight prices for specified routes and dates.
- Sends SMS notifications when flight prices drop below a predefined threshold.

## Prerequisites

Before using this tool, ensure you have the following installed/configured:

- Python 3.x
- Required Python packages (install via `pip`):


## Setup

1. Clone the repository:
 ```bash
 git clone https://github.com/your_username/flight-deals.git

**Add your keys** 


FLIGHT_SEARCH_API_KEY = 'your_flight_search_api_key'

TWILIO_ACCOUNT_SID = 'your_twilio_account_sid'

TWILIO_AUTH_TOKEN = 'your_twilio_auth_token'

TWILIO_PHONE_NUMBER = 'your_twilio_phone_number'

