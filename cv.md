# Miraslau Rabikau

## 1. Contact Info
* **Mobile Phone** +375 (44) 772-02-13
* **Email:** m.rabikau2408@gmail.com
* **GitHub:** [@Miroslau](https://github.com)
* **LinkedIn:** [Miraslau Rabikau](https://www.linkedin.com/in/miraslau-rabikau-9190451b8/)
* **Telegram:** [@Mr_Myron](https://t.me)
* **Location:** Belarus, Gomel

---

## 2. About me
My name is Miraslau. I am a React and React-Native developer with 5 years of commercial experience. When I’ve been working, I’ve had both large and small projects, including some development from scratch, which has given me a clear understanding of how to perform well both independently and as part of a team.

I enjoy collaborating with a team and believe that clear communication is just as important as development skills. This involves not only developer interactions but also understanding business needs and the ability to suggest new ideas. It’s about working not just to ticket requirements, but also within the context of deadlines, writing clean and understandable code.

---

## 3. Professional skills
* **Programming Languages:** JavaScript, TypeScript
* **Frameworks & libraries:** React, Next, React Native, Redux, Redux Toolkit, Redux-Thunk, Webpack, Vite
* **Databases:** MySQL, PostgreSQL, MongoDB, Firebase.
* **Source Control Systems:** Docker, Docker Compose, CI/CD.

---

## 4. Experience

### My AI Social App
**Innowise** | Sep, 2024 - Jul, 2026

**Description:**
This project is the front-end for a modern government social support portal, designed to make applying for financial assistance a seamless and accessible experience for all citizens. The core of the application is a user-friendly, multi-step form wizard that guides users through the process efficiently.

**Responsibilities & Achievement:**
* Implemented custom component to communicate with AI bot in real time
* Integreate API to send the message to AI bot
* Implemented long pooling to get new notification after response from the server

**Stack:** React, JavaScript, ANT Design, Redux Toolkit, GPT API

**Source Code:** [Github Repository](https://github.com/Miroslau/my-ai-social-app)

---

## 5. Code Example
```
class LRUCache {
    private capacity: number;
    private cache: Map<number, number>;
    constructor(capacity: number) {
        this.capacity = capacity;
        this.cache = new Map();
    }

    get(key: number): number {
        if (!this.cache.has(key)) return -1;
        const value = this.cache.get(key);

        this.cache.delete(key);
        this.cache.set(key, value)

        return value;
    }

    put(key: number, value: number): void {
        if (this.cache.has(key)) {
            this.cache.delete(key);
        } else if (this.cache.size >= this.capacity) {
            const oldValue = this.cache.keys().next().value;
            this.cache.delete(oldValue)
        }

        this.cache.set(key, value)
    }
}
```

---

## 6. Education

### Gomel State Technical University P. O. Sukhoi
* **Majority:** Information system and technologies
* **Degree:** Bachelor degree
* **Year:** 2016 - 2020


---

## 7. English

* **Level:** <B2 (Upper-Intermediate)>
