- **NEVER EVER commit binary files to Git.**
  - We do not use Git LFS either.

- **Do not modify the global Git configuration on shared computers.**  
  - In particular, DO NOT set `user.email` and `user.name` globally.

- **NEVER store credentials on shared computers.**  
  - If necessary, use the credential cache helper, ensuring the timeout is set to **600 seconds or less.**  
    ```sh
    git config --local credential.helper "cache --timeout=600"
    ```
