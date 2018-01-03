# appengine-redirect
HTTP Redirect on Google App Engine


## Deploy on Google Cloud Platform

Remember to change **http://example.com** with your real domain.

    git clone https://github.com/lucab85/appengine-redirect.git
    cd appengine-redirect/
    sed -i 's#http://example.com#http://yourrealdomain.com#g' *
    gcloud app deploy
