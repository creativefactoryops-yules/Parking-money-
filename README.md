pip install flask 
# Parking-money-from flask import Flask
app = Flask(__name__)

@app.route('/')
def home():
return '<h1>Parking Spot $25</h1><a href="https://buy.stripe.com/bJe14m6QHclw13k1BA8Zq00">BUY NOW</a>'

if __name__ == '__main__':
app.run()
