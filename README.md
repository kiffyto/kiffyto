package main

import "fmt"

type Person struct {
  name string
  username string
  age int
  hobbies []string
  job string
}

func main() {
  var me = new(Person)
  
  me.name     = "Niño Infiesto"
  me.username = "KIFFY"
  me.age      = "20"
  me.job      = "MODI FILE CLONE | Web developer"
  me.hobbies  = []string{"code", "anime", "music"," guiterist"," gaming"}
  
  fmt.Println(me)
}
