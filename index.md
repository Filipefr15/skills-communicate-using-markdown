# xD
## xD
### xD
#### xD
##### xD
###### xD

short commit message (i guess)

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

``` golang
type tokenEnvelope struct {
	XMLName xml.Name `xml:"Envelope"`
	Body    struct {
		ExecuteResponse struct {
			Erro       string `xml:"Erro"`
			Token string `xml:"token"`
		} `xml:"GET.ExecuteResponse"`
	} `xml:"Body"`
}

```

