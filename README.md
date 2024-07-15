# aa-github-actions

## Commit Message Commands
 - [no ci]: Do not run Action for this commit

## Logs
### Log Group
```
echo "::group::My group title"
echo "Inside group"
echo "::endgroup::"
```

### Log Level
**Display a log with log level**<br>
```echo "::error title: title=<error name>, file=<filename>, line=<line number>, endLine=<end line number>, col=<column number>, endColumn=<end column number>::Missing semicolon"```

### Log Mask
```
echo "::add-mask::Secret String"
echo "Secret String"
```

#### Small change to test workflow
