---
title: CISSP General Axioms
---

{{< toc >}}

## 1. Number 1 goal is to protect life
    Scenario: Building is on fire, they want you to run into building to get backup tapes.
    Always assume getting people out of the building is first priority even when stated otherwise.

## 2. Everyone is responsible for security
    Example: A Janitor with no login is responsible too.
    After he sweeps server room, he must lock the door behind him.

## 3. Senior Management is ultimately Responsbile for security
    CISO is accountable, but senior management is responsible.
    Senior management writes the security policy, CISO uses that to do their job
      - If there is a breach CISO is fired, senior management puts another CISO in place.

## 4. Never spend more for a control than what you are protecting.
    (Single loss expectancy  * Annual rate of occurance)
    Example: $500 car that you pay $1500 a year on to protect. Not a good investment.

## 5. We don’t accept risk, only senior management can accept risk.
    We advise on what risks to accept.

## 6. Can't transfer ultimate responsibility, just some of the fallout.
    Example: Transfoer some financial impact with insurance

## 7. If you're reading a network question and it covers layer 1-4, recheck the model
    TCP/IP or OSI?

## 8.Training and awareness are mandatory. This includes cross-training
    AKA Staffing for resilience

## 9. Paper is a media
    Consider paper the same way you would a hard drive.

## 10. Patterns are bad
    Usually in reference to Cryptography

## 11. Senior Management can do whatever they want
    Our job is to make sure when they make the decision, they have a basic understanding of the risks.
    As long as they understand the risks, they can make whatever decision they want.

## 12. IT Security supports the business, not vice versa
    If it wasn't this way, we'd just get rid of half the things they do.

## 13. An attack on availability could be just slowing down the system, rather than knocking it out.
    Making a system run at degraded speed is a successful attack

## 14. Digital signatures don't do shit for confidentiality.
    They only provide integrity and non-repudiation.

## 15. No single control can be considered perfect.
    Does this mean you need multiple or that you should assume each one is inherently flawed?

## 16. eCommerce = Encryption.
    If the exam mentions eCommerce, they want you to be aware of you handling credit cards.
      - PCI
    Requirement 4 = protect data in transit
      - Best way to protect data in transit? Encryption. (No way to inspect an encrypted payload)