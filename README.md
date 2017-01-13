## yesod-auth-typedcontent

This package provides a pluggable mechanism for allowing users to authenticate
with your site. It comes with a dummy plugin. Other packages are available
from Hackage. 

This is a fork, err, sort of, of the
primary [yesod-auth](https://hackage.haskell.org/package/yesod-auth) package.

Created I was not satisfied that the only option for utilising the pluggable
auth meant I was bound to using a purely HTML driven form and for some reason
forced to be happy that a failed auth would return a 200.

I'm still new to Yesod but these seemed like odd contraints that I could not
find a way by config or custom functions to be able to alter.

If this is madness then by all means let me know.
