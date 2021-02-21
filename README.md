---
description: >-
  A maid who faithfully serves the Knights of Favonius. She dreams of joining
  their ranks someday.
---

# Noelle

## ![](https://github.com/ctadhara/guides/tree/c07297899107b0a09657ebb0f459e28e3f5a9437/.gitbook/assets/element_pyro.png) Noelle

![](https://github.com/ctadhara/guides/tree/c07297899107b0a09657ebb0f459e28e3f5a9437/.gitbook/assets/bennett.png)

## **Attacks**

{% tabs %}
{% tab title="Favonious Bladework - Maid" %}
**Normal Attacks**  
Perform up to 4 consecutive strikes.

| String | Talent 6% | Frames | Motion Value |
| :--- | :--- | :--- | :--- |
| 1-Hit | 115% |  |  |
| 2-Hit | 106.63% |  |  |
| 3-Hit | 125.38% |  |  |
| 4-Hit | 164.88% |  |  |

Optimal damage is a 4-hit cancel when hitting all targets or 3-hit cancel when the fourth hit won't hit all enemies.

**Charged Attack**  
Noelle consumes 40 stamina a second to keep spinning.       **** At the end, perform a more powerful slash.

| String | Talent 6% | Frames | Motion Value |
| :--- | :--- | :--- | :--- |
| Spin | 73.75% |  |  |
| Final hit | 131.5% |  |  |

Enemies struck by Noelle's charged attack will be staggered or launched.

**Plunge**

| Damage Type | Talent 6% |
| :--- | :--- |
| Plunge Impact | 108.41% |
| Low Plunge DMG | 216.78% |
| High Plunge DMG | 270.77% |

If performing a Jump when breastplate expires Noelle can gain enough height to use a plunge attack.
{% endtab %}

{% tab title="Breastplate" %}
Summons a shield that deals damage in a small radius around Noelle.

* Shield strength scales with Noelle’s current Def.
* When hitting an enemy there is a chance to heal all characters in the party. 
* The amount healed scales with Noelle’s current Def
* The Shield possesses the following properties:
  * 150% DMG Absorption Efficiency against all damage.
  * Can trigger Crystallize when hitting a target with a element applied to them.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Type</th>
      <th style="text-align:left">Talent 6%</th>
      <th style="text-align:left">Cooldown</th>
      <th style="text-align:left">GU</th>
      <th style="text-align:left">Particles</th>
      <th style="text-align:left">Frames</th>
      <th style="text-align:left">Motion Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Base DMG</td>
      <td style="text-align:left">168%</td>
      <td style="text-align:left">24 sec</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">2</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Healing</td>
      <td style="text-align:left">
        <p>29.79%</p>
        <p>Def + 163</p>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">3</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Healing chance</td>
      <td style="text-align:left">123.2% + 134.4%</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Shield Scaling</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">Duration</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>

* Max hold duration is x seconds, after which Bennett will use a Level 2 Passion Overload by default. 
* Having knockback resistance will prevent the explosion from knocking back Bennett after casting a Level 2 Passion Overload.
{% endtab %}

{% tab title="Fantastic Voyage" %}
Bennett performs a jumping attack to create **Inspiration Field**, dealing Pyro DMG.

**Inspiration Field**

* If the health of a character within the AoE of **Inspiration Field** is less than or equal to 70%, their HP will continuously regenerate based on Bennett’s max HP. 
* However, if the health of the character is greater than 70%, gain an ATK bonus based on Bennett’s base ATK.
* Continuously imbues characters within the AoE with Pyro.

| Effect | Talent 6% / Data |
| :--- | :--- |
| DMG | 325.92% |
| HP Regeneration | 8.4% Bennett Max HP + 914 |
| ATK Bonus Ratio | 78.4% Bennett **Base ATK** |
| Duration | 12s |
| Cooldown | 15s \(non-scaling\) |
| Energy Cost | 60 |
| GU | 2U |
| Imbue | 1U |
| Frames |  |

* Bennett field does not apply the buffs instantaneously on swap. **Inspiration Field** applies the ATK bonus and healing on the same tick every second. If you swap after the tick occurs, you will need to wait for the next tick to receive the ATK bonus.
* **Inspiration Field** will apply the ATK Bonus and **C6: Fire Ventures with Me** will also apply the Pyro DMG bonus immediately on cast.
* The bonus ATK from **Inspiration Field** ONLY scales with Bennett's base attack, including buffs like Noblesse Oblige \(2\).
{% endtab %}
{% endtabs %}

## **Ascension Passives**

{% tabs %}
{% tab title="Passive" %}
### It should be safe...

When dispatched on an expedition in Mondstadt, time consumed is reduced by 25%
{% endtab %}

{% tab title="Ascension 2" %}
### Rekindle

Decrease passion overload’s cooldown by 20%.
{% endtab %}

{% tab title="Ascension 4" %}
### Fearnaught

Within the Inspiration Field created by Fantastic Voyage, Passion Overload takes the following effects:

* CD is reduced by 50%
* Bennett will not be launched by the explosion of Passion Overload: Charge Level 2.
{% endtab %}
{% endtabs %}

## Constellations

{% tabs %}
{% tab title="C1" %}
### Grand Expectation

Fantastic Voyage’s ATK increase no longer has an HP restriction, and gains an additional 20% of Bennett’s Base ATK.
{% endtab %}

{% tab title="C2" %}
### Impasse Conqueror

When Bennett’s HP falls below 70%, his Energy Recharge is increased by 30%.
{% endtab %}

{% tab title="C3" %}
### Unstoppable Fervor

Increases the level of Passion Overload by 3.
{% endtab %}

{% tab title="C4" %}
### Unexpected Odyssey

Using a Normal Attack when executing the second attack of Passion Overload’s Charge Level 1 allows an additional attack to be performed. This additional attack does 135% of the second attack’s DMG.

| Attack | Talent 6% | Talent 9% | Motion Value |
| :--- | :--- | :--- | :--- |
| Passion Overload Level 1 + Normal Attack | 117.6% + 128.8% + 173.88% | 149.6% + 163.2% + 220.3% |  |
{% endtab %}

{% tab title="C5" %}
### True Explorer

Increases the Level of Fantastic Voyage by 3.
{% endtab %}

{% tab title="C6" %}
### **Fire Ventures with Me**

Sword, Claymore, or Polearm-wielding characters inside Fantastic Voyage’s radius gain a 15% Pyro DMG Bonus and their weapons are infused with Pyro.

* Pyro Infusion lasts 2 seconds upon leaving **Inspiration Field**.
* The Pyro DMG bonus will apply to the Fantastic Voyage damage.
* Pyro infused autos have 1U worth of Pyro applcation.
{% endtab %}
{% endtabs %}

## **External Links**

* [**Honey Hunter**](https://genshin.honeyhunterworld.com/db/char/bennett/)
* [**Genshin Impact Fandom**](https://genshin-impact.fandom.com/wiki/Bennett)
* [**Bennett Mains Discord**](https://discord.gg/qrjeEyejsd)

**Tags:** [Field Buffs](https://library.keqingmains.com/mechanics/combat/field-buffs), [Elemental Gauge Theory](https://library.keqingmains.com/mechanics/combat/elemental-reactions/elemental-gauge-theory)

**Evidence Vault:**

