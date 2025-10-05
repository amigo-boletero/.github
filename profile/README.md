## Hi there 👋

```mermaid
usecase diagram

actor Customer
actor "Online Retailer" as Retailer

rectangle "Online Shopping System" {
  usecase (Browse Products)
  usecase (Add to Cart)
  usecase (View Cart)
  usecase (Checkout)
  usecase (Make Payment)
}

Customer --> (Browse Products)
Customer --> (Add to Cart)
Customer --> (View Cart)
Customer --> (Checkout)
Retailer --> (Make Payment)

(Checkout) ..> (Make Payment) : <<include>>
```

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
