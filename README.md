# 🔮 write to your future self <3

cornelli is your small terminal app for the times when you really desire to give your future self pats for the work you do; or for expressing any thoughts to them.

### Universal install

```bash
cargo install nelli
```

### Using Homebrew

```bash
brew install hitblast/tap/cornelli
```

### Pre-baked releases

Get the goodie from [GitHub Releases](https://github.com/hitblast/cornelli/releases).

<br>

## 🪄 Usage

Get started by setting a password. You can temporarily set this:

```bash
# on unix
export CORNELLI_PASS="whateveryouwant"

# on windows
set CORNELLI_PASS=1234
```

> [!NOTE]
> You may put this as your permanent environment variable but this **may be destructive for certain cases**. I would like to keep it this way since during execution, you can also pass the password *before* the command as a prefix.

Then, by putting your thoughts away for a certain duration, you encrypt your letter away.:

```bash
# unlocks after 20 days, 1 hour, 2 minutes and 1 second
nelli keep "Miss the board games with friends?" -d 20d1h2m1s
```

As time goes, let this command surprise you once in a while if you feel like it:

```bash
nelli mailbox
```

Hopefully you'll enjoy what comes next! :3

> [!NOTE]
> On a special note - if you use different passes for different capsules, you can get a plethora of capsules which all unlock when different ones of these passwords are provided, not revealing them in an instant, at all.

If you do wish to, however, make all your lost messages lost "forever", try:

```bash
nelli burn
```

<br>

## ☘️ Compiling

It's just a one-liner, use this command:

```bash
cargo build --release --quiet --locked
```

# 🪄 Why

This is a Christmas project - a friend and I decided to spin up a friendly hackathon for building a time capsule of memories. And besides, what better way to set the mood for this day than creating something fun with the tools you have?

## License

Licensed under the [MIT License](./LICENSE).
