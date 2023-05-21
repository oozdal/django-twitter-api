# django-twitter-api 
django-twitter-api  allows you to tweet using your own frontend without interacting with the Twitter UI.

# What's the point? 
Just for fun. Your definition of fun is probably very different from programmers :)

# How can I use this django-twitter-api for my own Twitter account?
You may clone this repo, and then create a conda environment using the following command lines

1) ```conda env create -f environments.yml -n twitter-api```

2) ```conda activate twitter-api```

3) export your own twitter credentials in your conda environments

```export TWITTER_API_KEY="PUT_YOUR_OWN_TWITTER_API_KEY"```

```export TWITTER_API_KEY_SECRET="PUT_YOUR_OWN_TWITTER_API_KEY_SECRET"```

```export TWITTER_ACCESS_TOKEN="PUT_YOUR_OWN_TWITTER_ACCESS_TOKEN"```

```export ACCESS_TOKEN_SECRET="PUT_YOUR_OWN_TWITTER_ACCESS_TOKEN_SECRET"```

4) Voila! Click http://127.0.0.1:8000/ and write your tweet and submit it. Have fun! :)


