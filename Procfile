web: npm start
worker:  node -e "setInterval(function(){console.log('working')}, 1000);"
clock:  node -e "setInterval(function(){console.log('tick')}, 1000);"
:javascript
  window.App = {
    STRIPE_PUBLISHABLE_KEY = '#{ENV.fetch('STRIPE_PUBLISHABLE_KEY')}'
  };
