---
published: true
---

## How to prevent .DS_Store file creation over network connections
To prevent Finder from creating .DS_Store files in remote folders, just run this in the terminal:

{% highlight ruby %}
defaults write com.apple.desktopservices DSDontWriteNetworkStores true
{% endhighlight %}