---
layout: default
title: Inpaklijst
has_children: true
---

Inpakken. Nooit leuk en het wordt nog erger als je dingen vergeet. Daarom hier een voorzet. Eerst een algemene lijst en dan onderaan nog wat specifieke lijsten. Je hebt immers niets aan een snowboard tijdens je weekend fietsen in de Ardennen.

{% for inpakCategorie in site.data.inpaklijst.categorieen %}

## {{ inpakCategorie.naam }}

{% for inpakitem in inpakCategorie.items %} - [ ] {{ inpakitem }}
{% endfor %}
{% endfor %}

# Algemene inpaklijst

Spullen die altijd wel mee moeten

- [ ] Sokken
- [ ] Kleding
- [ ] Jas
- [ ] Adapters en kabeltjes
- [ ] Zaklamp of Waka Waka's
- [ ] Zonnebril
- [ ] Pet
- [ ] E-reader
- [ ] Onderbroeken
- [ ] Schepje voor de koffie
- [ ] Scherp mes
- [ ] Slippers
- [ ] Aansteker
- [ ] EHBO Doos
