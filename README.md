# Add a favicon to your Enonic site

Need to add favicons to your Enonic XP site? This is the app for you!

> **Note:** Requires Enonic v6.4.1

## How to use

Using this is pretty straight forward. It will be much easier once it's
available in the [Enonic Market](https://market.enonic.com), but it's still
very doable.

### Step 1: Download `.jar`

Get the jar by downloading it from
[bintray](https://bintray.com/artifact/download/selbekk/maven/favicon-1.0.0.jar),
or alternatively cloning this repo and building it.

### Step 2: Deploy to your site

If you're developing locally, deploy via gradle like so:

```bash
$ ./gradlew deploy
```

You can also install it via the application tab in the Enonic admin panel. Just
click `install` and choose the JAR.

### Step 3: Apply the application to your site

In the content manager, select your site and click `edit`. Search for `Favicon`
in the `Applications` search box, and select it.

### Step 4: Upload your favicon image

Finally, upload your favicon image. We suggest it's a large square `.png` image
(at least 512 * 512 px), but JPG is also probably fine.

## Open open source

If you want to contribute, please create a pull request. If it's approved,
you'll get full contributor access, as well as your name on the contributors
list. We trust you!
