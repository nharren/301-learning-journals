# LJ Code 301 - Day 6

On day 6, I learned how to make AJAX calls usng jquery. I learned that there is a general method for calling ajax with `$.ajax()` and other methods which simplify common defaults, such as `$.get()` and `$.getJSON()`. In addition, I learned about representational state transfer (REST) apis, which is an architectural style consisting of a set of constraints. Those constraints are: 
1. Starting from no constraints (aka. null style).
2. Client-server style to separate user interface concerns from data storage.
3. Stateless communication to improve:
  * Visibility: A monitoring system doesn not have to loo beyond a single request to determine the full nature of the request.
  * Reliability: Eases the task of recovering from partial failiurs.
  * Scalability: Allows the server to quickly free resources and not have to manage them across requests.
4. Cache to improve network efficiency.
5. Uniform interface to improve adoption.
6. Layers to encapsulate legacy services and simplify components.
7. Code-On-Demand to reduce the need for features to be pre-implemented and thus improves extensibility.