# Submission Check

As a student you have to submit a lot of tasks
to the lecturer. And usually the only reply you
get is that you passed or not. This is a situation
we want to change.
Submissition Check is a system to automatically check
your submissions and give an immediate result.
With the result we want to provide suggestions
to the students about their mistakes.
But also collect the most common mistakes and
present them to the lecturer such that they
can address them in the lectures.


## Build and Run in Production
We provide the application and all dependencies via docker containers
that are already defined in the `docker-compose.yml` file.

Build the applications by executing

```bash
./gradlew dist
```

Then run the app on a docker system in background by executing

```bash
docker-compose up -d
```

## Supervised By

* Frank Kammer