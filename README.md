
In the terminal, ensure you are in the ../../todo_list directory and 
run the below command to set the NODE_OPTIONS environment variable with 
the –openssl-legacy-provider flag.

```
export NODE_OPTIONS=--openssl-legacy-provider
```

This ensures that the specified OpenSSL provider is used when running 
your Node.js application, potentially resolving certain cryptographic issues.
