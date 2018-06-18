# Ver-todas-las-respuestas-de-alamofire-RAW-Swift

```

print("Request: \(response.request)")
  print("Response: \(response.response)")
	print("Error: \(response.error)")
						
	if let data = response.data, let utf8Text = String(data: data, encoding: .utf8) {
		print("Data: \(utf8Text)")
	}
            
            ```
