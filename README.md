# Eat This Much Withings Sync

Pretty much what the header says, an application to listen for withings weight measurements and synchronize them to Eat this much. I'm hoping to implement a way to do this without storing user credentials, but I'm not really seeing a way to do so.

## Starting up
Standard rails process, requires postgresql 9.6.3

- download
- bundle
- rails s

## Using
If I come up with a publicly hosted option, I'll list that here, but I don't know that I want to assume that responsibility. In the meantime, you could potentially setup a web service somewhere running the app, just be sure to set local environment values for ETM_SYNC_API_KEY and ETM_SYNC_API_SECRET from your own application registered at withings. ( Still haven't gotten to the ETM user values ... will list them here when I do )
