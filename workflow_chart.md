Workflow Chart for the Decentralized-Health-Data-Cooperative Project

WEBPAGE
1. HOME PAGE
    a. Login tab
    b. Register tab
    c. Medical Institutions tab
    d. Services
    e. About tab(about page default)

2. LOGIN PAGE
   // application remembers login option
    a. Medical Institution Login
    b. Login as Medical Institution Administrator
    c.
    d. Login as client

        A. Medical Institution Login [Medical Institution]
            -Fields: Institution ID, Passkey

        B. Login as Medical Institution Administrator
                --Administrator Name
                --Administrator Passkey

    //  Under Medical Hospital Home page [like a profile page or dashboard with profile pics]
        C. Sign in under a Medical Institution {Medical Institution personnel}
            --personnel name
            --personnel Passkey
            --Medical Institution pass token

        D. Login as Client
            -Fields: User ID, Passkey

    // Forgot password 
    // Not Registered? Register

3. REGISTER PAGE
    a. Register Medical Institution
    b. Register as Medical Institution Administrator
    c. # Under Medical Institution Dashboard
        Register as Medical Institution personnel
    d. Register as client

        A. Register Medical Institution

            ---Hospital Administrator Login
                --Administrator Name
                --Administrator Passkey
                // Administrator Forgot Password
                // Not an Administrator? Register.
           ---Medical Institution Registration Page proper
               --Fields: Institution Name, Address, Medical License number, CAC License number 

        B. Medical Institution Administrator Register
            --Fields: Administrator Name, Administrator Role, Administrator Address, Administrator Phone, Administrator Email, CAC License number, Medical Practice License Number and other required license numbers, PassKey
            // Administrator Login button

        #Under Hospital dashboard
        C. Medical Institution Personnel Register 
            --Fields: User Names, NIN, email, Gender, Date of Birth, Personnel Role, Passkey

        D. Register as Client
            --Fields: User Names, NIN, email, Gender, Date of Birth, Passkey

4. END PAGES
    A. Medical Institution Page
        --Client Record Download/Update 

    B. Hospital Administrator Page
        --Add/Remove personnel
        --Client Record Download/Update
        --Hospital Records Analytics

    C. Medical Institution Home/Profile Page

    D. Client Page
        --AI agent
        --Patient Records (if initialized by a Medical Institution)
