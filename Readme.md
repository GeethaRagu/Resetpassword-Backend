# Reset password


'/register-user' : Creates user with username,email and password.

'/login-user' : Checks whether the user emailid and password matches.

'/forgot-password' : Sends email to user email id with link to reset along 
                    with random string.  

'/checkstring/:str' : Once the user redirects from reset link, the random string 
                        generated is checked.

'/reset-password': Password is updated with new one and random string is cleared.