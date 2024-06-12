`ruby compiler.rb | node`

1. TEST gets evaluated
2. console.log(f(1,2)) looks for fn f()
3. fn f() which is defined in test.src gets evaluated
4. fn f() tries to call fn add() which is defined in RUNTIME
5. helper fn add() in RUNTIME gets evaluated
6. TEST's console.log returns value
