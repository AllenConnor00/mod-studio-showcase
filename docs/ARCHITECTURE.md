# Mod Studio architecture — public overview

```text
User brief / idea proposal
           |
           v
Clarification and approval
           |
           v
Persistent project controller
           |
           +--> Model / planning boundary
           |
           +--> Versioned tool adapters
           |
           +--> Asset validation and previews
           |
           v
Bounded build / test / review
```

The private repository includes an early agentic controller and a separate deterministic skin-workstation component. The latter validates and renders approved skin assets without granting the visual component unrestricted project modification authority.

Full automation and support for a wide range of mod sizes are design objectives, not established results.
