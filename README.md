a := []byte{'1','2','3','4','5'}
b := string(a)

a[0] = 'a' 

fmt.Printf("%s\n", a)
fmt.Printf("%s\n", b)
