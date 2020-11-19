# PragmaBrewery Exam

![screencapture-localhost-8000-2020-11-20-01_59_32](https://user-images.githubusercontent.com/1567724/99705047-2f4de700-2ad4-11eb-9c4d-4e6bb3bc09fa.png)

```
git clone git@github.com:yowmamasita/pragmabrewery-app.git
cd pragmabrewery-app
git submodule update --init --recursive
docker-compose up
```

Go to `localhost:8000` for the frontend, backend is on `localhost:8080`

## NotFAQ

### What are your challenges building this project?

I haven't used Node from scratch as the microfrontend "monolith" I'm working on right now is something I wasn't involved building. Setting up the backend project, initially I went with vanilla JS because I want to simplify the clean architecture appraoch I'm going with. But then after some hardships and weird development experience (intellisense, etc.) I switched to using Typescript.

I feel that I spent so much time on the backend so when I was working on the frontend, I'm a half empty glass. That's why on the frontend I can't make eslint work properly so I just went ahead without it.

### What is the part you're proudest of in this project?

I think it'd be the thermometer component as this is something I haven't really done a long time (coding with SVGs). I think graphical interfaces is a really fun task.

It was also my first time doing clean architecture on Node (backend).

### How do you ensure that Shane is alerted when a beer drops or rises below/above safe temperature range?

I was planning to add a sound to alert Shane but I didn't have enough time to do it. It will definitely help Shane if Shane is someone who is visually impaired.

Right now, what I have implemented is just eye-catching UI signals.

### What's next for PragmaBrewery?

I was planning to add a circuit breaker (say Heroku cold boot takes the whole winter season to finish), a proper error tracking and observability, a central logging middleware in the backend.

On the frontend, I don't feel the UI is that appealing but I made sure it serves the purpose. But currently linter config is missing and proper configuration workflow through config files.

For both components, adding more tests - unit and integration, will definitely come a long way.

> Ben Sarmiento
