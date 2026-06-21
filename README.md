# Tesla FleetAPI Setup

This repository hosts the files needed for Tesla FleetAPI authentication.

## Files

- `code.html` - Landing page that extracts the OAuth authorization code
- `.well-known/appspecific/com.tesla.3p.public-key.pem` - Public key for FleetAPI partner registration

## Usage

After Tesla redirects to this site, the authorization code will be displayed on the page for you to copy and paste into the pypowerwall setup script.

## Security Note

Only the **public** key is hosted here. The private key remains secure on your local machine and should never be shared or uploaded to any public repository.
