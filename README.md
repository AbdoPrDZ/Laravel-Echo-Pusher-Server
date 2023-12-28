# Laravel Echo Server (Pusher) ^0.0.1

## Versions

| Package                       | Version   | URL Source                                                             |
| ----------------------------- | --------- | ---------------------------------------------------------------------- |
| laravel                       | 10.x      | [laravel](https://laravel.com/docs/10.x)                               |
| pusher_client_fixed (flutter) | 0.0.2+2   | [pub.dev](https://pub.dev/packages/pusher_client_fixed)                |
| laravel_echo_null (flutter)   | 0.0.5+4   | [pub.dev](https://pub.dev/packages/laravel_echo_null)                  |
| storage_database (flutter)    | 0.0.9+4   | [pub.dev](https://pub.dev/packages/storage_database)                   |

## Configure Steps:

* configure pusher on your project see ([Leravel Pusher Configuration](https://laravel.com/docs/10.x/broadcasting#pusher-channels))
* create your user model&migration.
* configure sanctum auth middleware ([sanctum](https://laravel.com/docs/10.x/sanctum)) or any other middleware.
* configure broadcasting (read [broadcasting](https://laravel.com/docs/10.x/broadcasting) for more information).
* edit broadcasting auth middleware and set it to your middleware you use like ```Broadcast::routes(['middleware' => 'auth:sanctum']);```.
* create new user for test.
* login user and get token for test.
* try to connect the laravel echo client, this some examples:
    * [flutter using laravel_echo_null](https://github.com/AbdoPrDZ/laravel_echo_null/tree/main/example).
    * [flutter using storage_database](https://github.com/AbdoPrDZ/storage_database/tree/main/example).
    * [js using laravel_echo](https://github.com/AbdoPrDZ/Laravel-Echo-Pusher-Server/tree/main/resources/js/bootstrap.js).
* create your events and test it.

## Note: You can message me if there any problem.

# Contact Us

GitHub Profile: <https://github.com/AbdoPrDZ>

Telegram (+213778185797)
WhatsApp (+213671435034)

Facebook Account: <https://www.facebook.com/AbdoPrDZ>
