# Static Server

## Adding more handlers

into `api` folder each file is a handler, you can add more handlers by creating a new file in the `api` folder.

example of basic handler

```golang
func Handler(w http.ResponseWriter, r *http.Request) {
	fmt.Fprintf(w, "handler")
}
```

## Deploy to Vercel

run the following command to deploy to vercel

```bash
vercel .
```

and follow the instructions

That's it! Your static server is now running on Vercel.

Now you can visit the URL that was output by the `vercel` command to see your static server in action.

### Happy coding 🎉
