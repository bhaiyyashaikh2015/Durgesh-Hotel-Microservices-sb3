# Durgesh-Hotel-Microservices
OKTA | ApiGateway | Services | FeignClient | RestTemplate | EurekaServer | ConfigServer | Resilience4j | Circuitbreaker | Ratelimiter



- These microservices built using spring boot 3.3.x framework and secured with spring security and okta.

Steps to run:

1. Start ServiceRegistry app
2. Start ConfigServer app
3. Start ApiGateway app
4. Start HotelService app
5. Start RatingService app
6. Start UserService app



NOTE: 
1. OKTA login is implemented on API gateway, so need to generate JWT token from API gateway service.
2. Internal API security is implemented on some services (Rating | Hotel) which can not be accessible directly, the call should go through some other API only.
