# kafka-docker

**1. To run kafka use command:**

```bash
docker-compose up --build
```

Now kafka & consumer is running in this terminal.

**2. Run producer in other terminal to enter message.**

```bash
cd kafka-docker
docker-compose run producer
```

**3. In producer terminal type messages**

```text
> Hello!
> How are you?
> This is kafka producer.
>
```

**4. In consumer terminal you will see messages.**

```text
Hello!
How are you?
This is kafka producer.
```