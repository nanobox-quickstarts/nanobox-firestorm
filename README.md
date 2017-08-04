![Firestorm from scratch](https://guides.nanobox.io/assets/quickstart-icons/firestorm.png)

# Firestorm from scratch

Run a Firestorm app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-firestorm.git

# cd into the firestorm app
cd nanobox-firestorm
```

## Run the app

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local firestorm.dev

# Start Nanobox
nanobox run

# migrate your repo
mix ecto.migrate

# start your server
mix phx.server
```

## Check it out

Visit your app at <a href="http://firestorm.dev:4000" target="\_blank">firestorm.dev:4000</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where elixir is installed,
elixir -v

# and your code is mounted
ls
```

<!-- ## Now What?
For more details about running firestorm apps with nanobox visit [guides.nanobox.io/elixir/firestorm/](https://guides.nanobox.io/elixir/firestorm/) -->

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
