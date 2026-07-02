# Sable Bluff Analysis

## 🎯 Objective

Visualize ATT&CK techniques associated with:

- APT29
- DarkComet
- Active Directory Configuration mitigations

## 📊 Scoring Model

| Score | Meaning |
|--------|---------|
| 80 | Techniques used by APT29 |
| 50 | Techniques used by DarkComet |
| 25 | Techniques mitigated by Active Directory Configuration |

## 🎨 Color Legend

The ATT&CK Navigator heatmap uses color intensity and color variation to represent technique scores:

| Color | Score | Meaning |
|--------|--------|---------|
| 🔴 Red | 80 | Techniques associated with **APT29** |
| 🟡 Yellow | 50 | Techniques associated with **DarkComet** |
| 🟢 Blue-Green | 25 | Techniques mitigated through **Active Directory Configuration** |
| ⚪ Uncolored | 0 | No association or mitigation identified in this analysis |

As the score increases, techniques become more visually prominent, helping analysts quickly identify high-priority threats and defensive opportunities.

## 🔍 Analysis Summary

This ATT&CK Navigator layer combines adversary behavior and defensive mitigation data into a single visualization. By overlaying threat actor techniques with Active Directory Configuration mitigations, defenders can quickly identify attack paths that may be reduced through proper identity and directory management.

## 💡 Key Takeaways

- Credential Access techniques represent a significant portion of the mapped attack surface.
- Several credential theft techniques can be mitigated through proper Active Directory configuration.
- Identity-focused defenses provide meaningful protection against common adversary tradecraft.
- Overlaying threat intelligence with mitigations helps prioritize defensive efforts.
- ATT&CK Navigator provides an effective method for visualizing and communicating security priorities.

## 🛠️ Technologies Referenced

- MITRE ATT&CK Framework
- ATT&CK Navigator
- Active Directory
- APT29 (Cozy Bear)
- DarkComet RAT

## 📁 Files

- `sable_bluff.json` → ATT&CK Navigator layer
- `Sable_Bluff.svg` → Exported ATT&CK Navigator visualization