# Wake Word Pocket Sphinx

Attempt to use pocket sphinx as a wake word detector.

## Conclusion

Does not listen well while music is playing.

Try it yourself.

## API

intent.action = "org.openintents.action.WATCH_WAKE_WORD"
// your Parcelled intent here, passed to startActivity
// optional, defaults to new Intent("Intent.ACTION_VOICE_COMMAND")
intent.extras.["Intent.EXTRA_INTENT"] =
// optional, supply the wake word app should respond to
// must be in cmudict-en-us.dict
intent.extras.["org.openintents.extra.WAKE_WORD"] = "computer"

## License

Falls under the same license used by CMU (LICENSE file unmodified and applies to this project)

