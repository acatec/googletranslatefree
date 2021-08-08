Google Translate FREE in golang

Note: This is not normal commercial Translator API
provided by Google.

Install:<br>
go get github.com/bas24/googletranslatefree

Example usage:

```go
	package main

	import (
		"fmt"
		"github.com/acatec/translategooglefree"
	)

	func main(){
		const text string = `Hello, World!`
		// you can use "auto" for source language
		// so, translator will detect language
		result, _ := translategooglefree.Translate(text, "en", "es")
		fmt.Println(result)
		// Output: "Hola, Mundo!"
	}
``` 
