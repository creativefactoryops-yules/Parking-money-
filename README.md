pip install flask 
# Parking-money-from flask import Flask
app = Flask(__name__)

@app.route('/')
def home():
return '<h1>Parking Spot $25</h1><a href="YOUR_STRIPE_LINK">BUY NOW</a>'

if __name__ == '__main__':
app.run()
