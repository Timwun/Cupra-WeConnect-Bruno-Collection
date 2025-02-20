# Cupra-WeConnect-Bruno-Collection

This is a bruno collection for the Cupra implementation of WeConnect.

## Bruno Download

[Bruno GitHub Page](https://github.com/usebruno/bruno)

## Getting started

First of all you need to download Bruno and open the collection.

After that, login into you Cupra account. This is done by right clicking on the Bruno Collection and going into the collection `settings` -> `Auth` -> `Get Access Token`.

Enter your credentials.

After that please run the `VW UserInfo` call to get your Seat/VW user UUID. It's the ID in `sub`.

Now you need to enter your `VIN` and the `Seat/VW user UUID` into the `Vars` section in the Bruno collection settings.

That's it, you're now ready to fire requests!

## What's supported

| What?                                     | Yes/No |
|-------------------------------------------|--------|
| Get climate info                          | ✅      |
| Changing climate settings                 | ✅      |
| Start/stop climate                        | ✅      |
| Get charging info                         | ✅      |
| Changing charging settings                | ✅      |
| Start/stop charging                       | ✅      |
| Car doors / windows status                | ✅      |
| Odometer                                  | ✅      |
| Next maintenance                          | ✅      |
| Parking position                          | ✅      |
| Warninglights                             | ✅      |
| Battery state / range                     | ✅      |
| Changing battery care mode                | ✅      |
| Sending destination to car                | ✅      |
| Getting charging stations around position | ✅      |
| Remote un/locking                         | ❌      |
| Switch on / off timed climate             | ❌      |
| HV battery temperature                    | ❌      |
