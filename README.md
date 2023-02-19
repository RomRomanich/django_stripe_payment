# Django examples

How to integrate Stripe Payment gateway into Django project

## Running this project


* the following environment variables need to be exported prior to use:
* you need to use the keys in "https://dashboard.stripe.com" API keys ('Publishable key' and 'Secret key')
```
STRIPE_PUBLIC_KEY = "pk_test_key"
STRIPE_SECRET_KEY = "sk_test_key"
```
* if you use your own environment; start by installing the requirements:

```
pip install --upgrade pip
pip install -r requirements.txt
```


* an apple phone purchase sample is used here
