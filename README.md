# portswigger-csrf

LAB1
CSRF VULNERABLILTY WITH NO DEFENCES
No prevention for CSRF and simple port request will work

LAB2
CSRF WHERE TOKEN VALIDATION DEPENDS ON REQUEST METHOD
CSRF token is needed for a post request, but not for a GET request

LAB3
CSRF WHERE TOKEN VALIDATION DEPENDS ON TOKEN BEING PRESENT
CSRF token is implemented in both GET and POST methods, but sending a POST request without a csrf token works. (CSRF token is not vaidated)

LAB4
CSRF WHERE TOKEN IS NOT TIED TO USER SESSION
Website does not check which CSRF token belongs to which user. Using the session of attacker (from inspect element in hidden input in form) and using it in payload
login as wiener(peter) in the victim browser and as carlos(montoya) in the attacker browser. Extract CSRF token from the attacker browser (using inspect element or any other method). Use this csrf token in the payload.

LAB5
