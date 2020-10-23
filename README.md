# mobtime

A websocket powered, collaborative mobbing timer.

On your desktop:

<p align="center">
  <img src="./docs/screenshot.png" width="30%" height="auto" />
</p>

And your phone:

<p align="center">
  <img src="./docs/screenshot-mobile.png" width="30%" height="auto" />
</p>

## Get up and running

```bash
yarn && yarn start
```

### Environment Variables

| Name            | Description                      | Default Value      |
| --------------- | -------------------------------- | ------------------ |
| PORT            | Port number to run the server on | 4321               |

### Sharing from your local computer

#### Using ngrok

```bash
yarn global add ngrok

ngrok http 4321 # replace 4321 with the port you do
```

## Contributing

Bug reports and suggestions are welcome, just create an issue. PRs are welcome, too.

## License

It's under [MIT](./LICENSE.md).


## Setup
''' Install Yarn
 https://linuxize.com/post/how-to-install-yarn-on-ubuntu-18-04/

Here are the key commands
> curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
> echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
> sudo apt update
> sudo apt install yarn

After install, run yarn.
> yarn test
> yarn start

Run tailwind
> yarn tailwind:dev
> or: yarn tailwind:prod

other links
> https://www.phusionpassenger.com/library/walkthroughs/basics/ruby/reloading_code.html

to run
> sudo PORT:80 ENSEMBLE_HOST=0.0.0.0 node ./index.js

example of how to run a service file to run on server
> http://13.53.192.207/
https://medium.com/@benmorel/creating-a-linux-service-with-systemd-611b5c8b91d6

