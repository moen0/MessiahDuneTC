# Dune: TBD NAME - A CK3 Total Conversion Mod
## Design Document v0.1

---
---

## Project Overview

### Vision Statement
Bring Frank Herbert's Dune universe to Crusader Kings 3,trying to capture the intricate political maneuvering, dynastic scheming, and religious manipulation that defines these books.

CK3's focus on character-driven gameplay, dynastic politics, intrigue make it a great fit for Dune:

- **Dynastic Politics**: Great Houses, succession crises, marriage alliances
- **Intrigue Systems**: Assassinations, schemes, kanly (formal vendetta)
- **Religious Manipulation**: Bene Gesserit influence, the Missionaria Protectiva
- **Feudal Hierarchy**: Emperor → Great Houses → Minor Houses → Planets

---

## Core Pillars I Want To Build On

### 1. Political Intrigue
The heart of Dune is political maneuvering. Every decision should have political ramifications:
- Landsraad politics and voting
- CHOAM entity incorparated somehow
- Kanly (formal vendetta between houses)
- Imperial favor and disfavor

### 2. Spice Economy
"He who controls the spice controls the universe."
- Spice as the primary economic driver
- Control of Arrakis as the ultimate goal
- Spice addiction mechanics
- Guild Navigator dependencies

### 3. Hidden Powers
- Bene Gesserit manipulation
- Spacing Guild leverage
- Mentats as advisors

### 4. Prophecy & Religion
Religion is a tool of control:
- Missionaria Protectiva (seeded prophecies?)
- The Kwisatz Haderach breeding program
- Orange Catholic Bible
- Fremen Zensunni beliefs

---

## Universe Adaptation

### CK3 → Dune Mapping

| CK3 Concept | Dune Equivalent |
|-------------|-----------------|
| Emperor | Padishah Emperor (House Corrino) |
| King | Duke/Archduke (Great House leader) |
| Duke | Count (Minor House leader) |
| Count | Baron/Planetary Governor |
| Baron | Sietch Naib / City Administrator |
| Religion | Faction allegiance (Bene Gesserit, Guild, etc.) |
| Culture | Planetary/Regional culture |
| Dynasty | Great House lineage |
| Council | House advisors (Mentat, Warmaster, etc.) |
| Lifestyle | Training path (Mentat, BG, Swordmaster, etc.) |
| Artifacts | Legendary weapons, stillsuits, etc. |

### Timeline Options Ideas



**Bookmark: Fall of House Atreides (10191 AG)* PRIMARY START
- Events of the first Dune novel
- House Atreides moves to Arrakis
- Harkonnen plotting


**Bookmark: The Regency (10210 AG)**
- After Paul's disappearance
- Alia as Regent
- Children of Dune era

---


## Map Design



```
THE KNOWN UNIVERSE (Empire tier)
├── IMPERIAL CORE (Kingdom)
│   ├── Kaitain System (Duchy) - Imperial Capital
│   │   ├── Kaitain (County) - Throne World
│   │   └── Salusa Secundus (County) - Prison/Sardaukar
│   └── Core Worlds (Duchy)
│       ├── Harmonthep
│       └── Other core systems
│
├── GREAT HOUSE TERRITORIES (Kingdoms)
│   ├── Atreides Domain
│   │   ├── Caladan System (Duchy)
│   │   │   └── Caladan (County)
│   │   └── Atreides Holdings
│   │
│   ├── Harkonnen Domain  
│   │   ├── Giedi Prime System (Duchy)
│   │   │   └── Giedi Prime (County)
│   │   └── Lankiveil System
│   │
│   └── [Other Great Houses...]
│
├── ARRAKIS (Special Kingdom - contested)
│   ├── Northern Territories (Duchy)
│   │   ├── Arrakeen (County) - Capital
│   │   ├── Carthag (County) - Harkonnen HQ
│   │   └── Sietch Tabr Region
│   ├── Deep Desert (Duchy) - Fremen
│   │   ├── Various Sietches
│   │   └── Hidden Reserves
│   └── Southern Territories (Duchy)
│
├── GUILD HOLDINGS (Kingdom)
│   ├── Junction (Duchy) - Guild HQ
│   └── Various holdings
│
├── BENE GESSERIT TERRITORIES (Kingdom)
│   ├── Wallach IX (Duchy) - Mother School
│   └── Chapterhouses
│
├── BENE TLEILAX (Kingdom)
│   └── Tleilax System
│
├── IX (Kingdom)
│   └── Ixian Confederacy
│
└── PERIPHERY (Kingdom)
    └── Minor houses, unexplored regions
```

---

## Factions & Houses

### The Major Powers

#### 1. House Corrino (Imperial House)
- **Homeworld**: Kaitain (current), Salusa Secundus (ancestral)
- **Specialty**: Military supremacy via Sardaukar
- **Key Characters**: Emperor Shaddam IV, Princess Irulan
- **Dynasty Legacy Focus**: Imperial Authority, Sardaukar Training

#### 2. House Atreides
- **Homeworld**: Caladan
- **Specialty**: Honorable leadership, military excellence
- **Key Characters**: Duke Leto, Lady Jessica, Paul
- **Dynasty Legacy Focus**: Popular Rule, Combat Excellence

#### 3. House Harkonnen
- **Homeworld**: Giedi Prime
- **Specialty**: Ruthless industrial power, intrigue
- **Key Characters**: Baron Vladimir, Feyd-Rautha, Rabban
- **Dynasty Legacy Focus**: Wealth Accumulation, Cruel Dominion

#### 4. House Fenring
- **Status**: Minor House, Imperial allies
- **Key Characters**: Count Hasimir Fenring, Lady Margot
- **Specialty**: Imperial assassins, BG connections

#### 5. House Richese
- **Specialty**: Technology (rivals to Ix)
- **Status**: Declining power

#### 6. House Ecaz
- **Specialty**: Arts, culture
- **Feud**: War with House Moritani

#### 7. House Moritani
- **Specialty**: Assassins
- **Feud**: War with House Ecaz

### Non-House Factions (Implemented as Religions/Special Mechanics)

#### The Spacing Guild
- Controls all interstellar travel
- Dependent on spice for Navigators
- Politically neutral (officially)
- **Mechanic**: Travel/trade permissions, Navigator breeding

#### The Bene Gesserit
- All-female order with superhuman abilities
- Runs breeding program for Kwisatz Haderach
- Places members in all Great Houses
- **Mechanic**: Hidden influence, trait breeding, Voice ability

#### The Bene Tleilax
- Masters of genetic manipulation
- Create gholas, Face Dancers
- Secretive and despised
- **Mechanic**: Cloning, Face Dancer infiltration

#### The Mentats
- Human computers (replacing banned AI)
- Serve as advisors to Great Houses
- **Mechanic**: Special councilor position, computation abilities

#### The Suk School
- Medical conditioning
- Supposedly incapable of causing harm
- **Mechanic**: Court physician position, immunity traits

#### The Fremen
- Native people of Arrakis
- Desert survival experts
- Zensunni religious beliefs
- Waiting for the Lisan al-Gaib
- **Mechanic**: Special culture, sandworm riding, desert warfare

---

## Game Mechanics

### 1. Spice System

**Spice Production**
- Only produced on Arrakis
- Controlled by CHOAM contract holder
- Requires harvesting operations
- Sandworm attacks as random events

**Spice Uses**
- Extends lifespan (longevity bonus)
- Required for Guild Navigators (interstellar travel)
- Bene Gesserit rituals
- Geriatric medicine
- Highly addictive

**Spice Economy**
```
Province Modifier: spice_production
- Holdings on Arrakis produce spice
- Spice stockpile as a resource
- CHOAM takes percentage as tax?
- Smuggling opportunities?
```

### 2. Kanly System (Formal Vendetta)

Replace vanilla feuds with Kanly:
- Formal declaration before Landsraad
- Rules of engagement (no atomics, etc.)
- Can escalate to War of Assassins
- Resolution through combat or negotiation

**Kanly States**:
1. Formal Declaration
2. Active Kanly (limited warfare)
3. War of Assassins (full intrigue)
4. Resolution (marriage, payment, or extinction)

### 3. The Landsraad

**Voting Mechanics**
- Great Houses have voting power
- Emperor has special veto
- Decisions affect all houses
- CHOAM directorship elections

**Landsraad Actions**:
- Declare house outlaw
- Approve/deny fief transfers
- Sanction kanly
- Trade agreements

### 4. Training Paths (Lifestyles)

Replace vanilla lifestyles with Dune-specific training:

**Mentat Path** (replaces Learning)
- Computation abilities
- Perfect memory
- Strategic analysis
- Sapho juice dependency

**Bene Gesserit Path** (Female only)
- The Voice (command ability)
- Prana-bindu training (combat)
- Truthsense
- Breeding program knowledge

**Swordmaster Path** (replaces Martial)
- Personal combat excellence
- Shield fighting
- Army command
- Ginaz training

**Political Path** (replaces Diplomacy)
- Landsraad influence
- CHOAM manipulation
- Alliance building
- Imperial favor

**Shadow Path** (replaces Intrigue)
- Assassination
- Intelligence networks
- Face Dancer management
- Poison expertise

### 5. Breeding Program

The Bene Gesserit breeding program as a game mechanic:
- Trait inheritance tracking
- Genetic bloodline management
- Kwisatz Haderach as ultimate goal
- Abomination risk

**Breeding Traits**:
- Prescience potential
- BG ability inheritance
- Ancestral memory access
- Enhanced abilities

### 6. Technology & Restrictions

**Butlerian Jihad Limitations**:
- No thinking machines (computers)
- Mentats replace AI
- Certain weapons banned
- Atomics forbidden against humans

**Allowed Technology**:
- Shield technology
- Lasguns (dangerous with shields)
- Stillsuits
- Ornithopters
- Spice harvesters

### 7. Unique Combat

**Personal Combat**
- Poison weapons
- Weirding Way (BG combat)

**Army Types**
- Sardaukar (elite Imperial troops)
- Fremen warriors (desert specialists)
- House troops (variable quality)
- Mercenaries
- Face Dancer infiltrators

---

## Religions & Cultures

### Religion System

Instead of traditional religions, implement faction allegiances:

#### Orange Catholic (Default "Religion")
- Standard Imperial faith
- Based on Orange Catholic Bible
- Most Great Houses follow this
- Ecumenical in nature

#### Zensunni (Fremen)
- Desert mysticism
- Lisan al-Gaib prophecy
- Sietch-based communities
- Syncretic Buddhist-Islamic roots

#### Bene Gesserit Influence
- Not a public religion
- Hidden manipulation
- Missionaria Protectiva as "heresies"
- Mother Superior as hidden "pope"

#### Tleilaxu Faith
- Secretive practices
- Genetic mastery as divine
- Despised by others

#### Guild Philosophy  
- Practical atheism
- Spice as holy substance
- Neutrality as doctrine

### Culture System

#### Imperial Cultures
- **Kaitaini** (Imperial court)
- **Caladanian** (Atreides domain)
- **Giedi** (Harkonnen domain)
- **Generic Great House** (various)

#### Fremen Culture
- Desert survival traditions
- Sietch social structure
- Water discipline
- Sandworm reverence

#### Specialist Cultures
- **Ixian** (technological focus)
- **Tleilaxu** (genetic masters)
- **Guild** (Navigator focused)

---

## Special Systems

### 1. Prescience
- Rare trait unlockable through breeding/spice
- Provides strategic advantages
- Can see possible futures
- Comes with drawbacks (paralysis of choice)

### 2. The Voice
- Bene Gesserit ability
- Forces compliance in targets
- Skill-based success chance
- Can be resisted by trained individuals

### 3. Ghola System
- Tleilaxu can create clones
- Risk of awakening past memories
- Ethical implications
- Strategic resurrection

### 4. Face Dancers
- Shapeshifting infiltrators
- Spy network enhancement
- Can replace key figures
- Detection possible

### 5. Sandworm Events
- Major threat on Arrakis
- Can devastate harvesting
- Fremen can ride them (cultural ability)
- Religious significance

### 6. Water Economy (Arrakis) ?
- Secondary resource on Arrakis
- Stillsuit requirement
- Sietch water reserves
- Death water rituals

---

## Development Roadmap

### Phase 1: Foundation (Weeks 1-4)
- [ ] Set up mod structure using Atlantis template
- [ ] Create basic map (galaxy representation)
- [ ] Implement core cultures (5-6)
- [ ] Implement core religions/factions
- [ ] Create major dynasties
- [ ] Basic landed titles structure
- [ ] First playable build (sandbox)

### Phase 2: Core Mechanics (Weeks 5-8)
- [ ] Spice economy system
- [ ] Basic Landsraad mechanics
- [ ] Kanly system
- [ ] Training paths (lifestyles)
- [ ] Council positions
- [ ] Basic events (100+ events)

### Phase 3: Characters & History (Weeks 9-12)
- [ ] All major characters from novels
- [ ] Dynasty trees
- [ ] Historical setup for bookmarks
- [ ] Character portraits (if custom)
- [ ] More events (200+ total)

### Phase 4: Advanced Systems (Weeks 13-16)
- [ ] Bene Gesserit breeding program
- [ ] Prescience mechanics
- [ ] Face Dancer system
- [ ] Sandworm events
- [ ] Advanced political events

### Phase 5: Polish & Content (Weeks 17-20)
- [ ] Additional bookmarks
- [ ] Flavor events (500+ total)
- [ ] UI customization
- [ ] Balance pass
- [ ] Localization complete
- [ ] Documentation

### Phase 6: Release Preparation
- [ ] Beta testing
- [ ] Bug fixes
- [ ] Steam Workshop preparation
- [ ] Community feedback
- [ ] Public release

---

## Resources & References

### Modding Resources
- [CK3 Wiki - Modding](https://ck3.paradoxwikis.com/Modding)
- [CK3 Mod Co-Op Discord](https://discord.gg/ck3modcoop)
- [Atlantis TC Template](https://github.com/bombusfrigidus/Atlantis)

### Dune References
- [Dune Wiki (Fandom)](https://dune.fandom.com)
- [Dune Encyclopedia](various sources)
- Original Frank Herbert novels

### Inspirations
- CK3 AGOT (Game of Thrones)
- Elder Kings 2 (Elder Scrolls)
- Realms in Exile (Lord of the Rings)


*Document Version: 0.1*
*Last Updated: January 21 2026*
*Status: Initial Planning*
