1. **3–5 sentences on when you'd pick a plain function vs `@dataclass` vs full class**.
    When there's a specific variable that has business internal rules and operations and either the variable or the operations are often called throughout the script I'd pick a class. When the operations are applied to multiple variables I'd pick a function. If I think of info I'd put on a table I should use dataclass while regular classes are a lot more flexible

2. **One concrete example from `python-utils` showing the `@dataclass` return pattern in action (link to the actual file/line)**.
In notebooks/week1_exercises, CQA is a perfect example of dataclass

3. **One R analogy you'd use to explain it to another R refugee**.