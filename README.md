# Heroku Sleep App

This app exists only to keep the Heroku application saved,  
but it **does not use a web dyno** and therefore does not consume Eco hours.

The Procfile contains a dummy process (`worker`) that is never scaled  
(unless you manually run it).