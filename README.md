# Wake Word Pocket Sphinx

Attempt to use pocket sphinx as a wake word detector.

## Conclusion

Does not listen well while music is playing.

Try it yourself.

## API

```lua
intent.action = "org.openintents.action.WATCH_WAKE_WORD"
-- your Parcelled intent here, passed to startActivity
-- optional, defaults to new Intent("Intent.ACTION_VOICE_COMMAND")
intent.extras["Intent.EXTRA_INTENT"] = nil
-- optional, supply the wake word app should respond to
-- must be in cmudict-en-us.dict
intent.extras["org.openintents.extra.WAKE_WORD"] = "computer"
```

You can do this from java, I just wrote it in lua for syntax highlighting

## License

Falls under the same license used by CMU (LICENSE file unmodified and applies to this project)

