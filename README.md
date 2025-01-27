# Meckano Autofill

Automatically fill all your missing non-rest days on Meckano with 9:00-18:00.

## Bookmarklet

1. Drag this link to your bookmarks bar:

<a class="bookmarklet" href="javascript:(function()%7Bfunction callback()%7BfillMonth()%7Dvar s%3Ddocument.createElement("script")%3Bs.src%3D"https%3A%2F%2Fakiva10b.github.io%2Fmeckano-autofill%2Findex.js"%3Bif(s.addEventListener)%7Bs.addEventListener("load"%2Ccallback%2Cfalse)%7Delse if(s.readyState)%7Bs.onreadystatechange%3Dcallback%7Ddocument.body.appendChild(s)%3B%7D)()">Meckano Autofill</a>

2. Go to your Meckano monthly report page
3. Click the bookmark and observe the magic

## Allow script injection
Install <a href="https://chromewebstore.google.com/detail/disable-content-security/ieelmcmcagommplceebfedjlakkhpden?hl=en">disable-content-security</a> plugin
and activate it before clicking on "Meckato autofill"

### Manual Bookmarklet

You can also just create a bookmark manually with this content:

```
javascript:(function()%7Bfunction callback()%7BfillMonth()%7Dvar s%3Ddocument.createElement("script")%3Bs.src%3D"https%3A%2F%2Fakiva10b.github.io%2Fmeckano-autofill%2Findex.js"%3Bif(s.addEventListener)%7Bs.addEventListener("load"%2Ccallback%2Cfalse)%7Delse if(s.readyState)%7Bs.onreadystatechange%3Dcallback%7Ddocument.body.appendChild(s)%3B%7D)()
```

## Demo

<video src="https://user-images.githubusercontent.com/78782036/177003404-29e2f9c3-0802-4355-9b41-3e0c5a7f4c63.mp4" data-canonical-src="https://user-images.githubusercontent.com/78782036/177003404-29e2f9c3-0802-4355-9b41-3e0c5a7f4c63.mp4" controls="controls" muted="muted" class="d-block rounded-bottom-2 border-top width-fit" style="max-height:640px;">
  </video>
