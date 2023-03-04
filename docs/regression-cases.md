# Regression cases

Prepared for this change. **Not executed.** Tests, manual checks, lint and builds require explicit user authorization. Use isolated fixtures; never run destructive cases against production.

| Case | Input or setup | Expected outcome |
| --- | --- | --- |
| Navigation | Follow Nosotros, Equipo, Tecnologías, Contacto links | Each resolves to its section |
| Form | Invalid email/blank required values then valid form | Native validation blocks invalid input; valid submission opens mail client with encoded values |
| Honest status | Prepare contact email | Status says send in email application; no false server-success message |
