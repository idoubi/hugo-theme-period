## Period

[Period](https://github.com/idoubi/hugo-theme-period) is a beautiful theme for Hugo. 

Reference from [Laruence's blog](https://www.laruence.com/)

view the [Demo Site](https://idoubi.cc)

## Usage

goto your hugo site 

```shell
cd {path-to-your-hugo-site}
```

get the theme

```shell
git clone https://github.com/idoubi/hugo-theme-period.git themes/period
```

copy theme config file 

```shell
copy themes/period/exampleSite/config.toml config.toml
```

run your hugo site 

```shell
hugo server -t period
```

## Example Config

```toml
theme = "period"

baseURL = "https://example.com"
copyright = "© idoubi.cc All rights reserved"
paginate = 20
title = "Period Theme"

[[menu.main]]
name = "Home"
url = "/"
weight = 1
[[menu.main]]
name = "Posts"
url = "/post/"
weight = 2
[[menu.main]]
name = "Abount"
url = "/about/"
weight = 3

[params]
logo = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQAl2chF0OuqvNKaMXWlh9GPn5vlHpSl0pXgQ&usqp=CAU"
subTitle = "A beautiful theme for Hugo."

[params.cdn.js]
highlightjs = "https://cdn.bootcdn.net/ajax/libs/highlight.js/10.3.2/highlight.min.js"
jquery = "https://cdn.bootcdn.net/ajax/libs/jquery/3.5.1/jquery.min.js"

[params.cdn.css]
highlightjs = "https://cdn.bootcdn.net/ajax/libs/highlight.js/10.3.2/styles/an-old-hope.min.css"

[params.comment]
repo = "{org}/{repo}"
show = false
theme = "github-light"

[params.widget.about]
description = "A fullstack developer"
logo = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQAl2chF0OuqvNKaMXWlh9GPn5vlHpSl0pXgQ&usqp=CAU"
show = true
title = "Idoubi"

[params.widget.qrcode]
show = false
title = "WeChat Official Account"
url = "https://blogcdn.idoustudio.com/idoubi-mp.jpeg"

[params.widget.projects]
show = true
title = "Open Source Projects"

[[params.widget.projects.items]]
description = "Daily news for golang"
name = "gonews"
url = "https://github.com/idoubi/gonews"

[[params.widget.projects.items]]
description = "Generate go struct according to SQL"
name = "sql2struct"
url = "https://github.com/idoubi/sql2struct"

[[params.widget.projects.items]]
description = "Request library used in golang"
name = "goz"
url = "https://github.com/idoubi/goz"

[params.widget.links]
show = true
title = "Friendly Links"

[[params.widget.links.items]]
title = "Hugo"
url = "https://gohugo.io"

[[params.widget.links.items]]
title = "Theme period"
url = "https://github.com/idoubi/hugo-theme-period"

[params.widget.categories]
show = true
title = "Categories"

[params.widget.tags]
show = true
title = "Tags"
```

## Preview 

![](./images/screenshot.png)



## Contributing

Any suggestions or pull request will be appreciated.
