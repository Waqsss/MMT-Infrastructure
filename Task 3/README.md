## Task 3: Cost Optimisation

Everyone is really happy that we have come so far at MMT and now want to save costs wherever we can. Our Cloud Architects have recommended that we upgrade our ECS clusters to now use Spot instances and 100% Fargate Spot capacity providers only, for all our non-production environments.

### The Challenge

Upgrade our ECS cluster and service to use Fargate Spot **only** if the environment name does not match `production`. If the environment is production, continue using the general Fargate capacity provider.
