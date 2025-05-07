```bash
#!/bin/bash

# Define CHashtager "class" as a function
function CHashtager() {
    # Properties
    local name="Omid"
    local role="Bug Producer :^D"
    
    # Method
    function sayHi() {
        echo "Hello world, I debug life!"
    }
    
    # Execute the method
    sayHi
    
    # Display properties
    echo "Name: $name"
    echo "Role: $role"
}

# Main program
echo "Creating CHashtager instance..."
CHashtager
```
