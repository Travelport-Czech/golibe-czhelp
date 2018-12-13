# Notifikace TravelFusion \(LowCost\)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Notifikace</th>
      <th style="text-align:left">Co znamená</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Travelfusion Rezervace potvrzena</b>
      </td>
      <td style="text-align:left">
        <p>Rezervace v pořádku vznikla.</p>
        <p>Pro zákazníka znamená: Vše je v pořádku a může letět.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Travelfusion Vypršel časový limit</b>
      </td>
      <td style="text-align:left">
        <p>Neobvyklá dočasná událost. 3 minuty je ověřována rezervace intenzivně
          po 5 sekundách a snažíme se získat její stav. Pokud jej nezískáme, pokračuje
          ověřování v delších intervalech po dobu 72 hodin. Pokud by nebyl výsledek
          do této doby zjištěn, bude kontrola ukončena a přijde notifikace o neuspěšné
          rezervaci - TF Rezervace neověřena robotem.</p>
        <p>Pro zákazníka znamená: Rezervace nebyla prozatím potvrzena.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Travelfusion Rezervace neověřena robotem</b>
      </td>
      <td style="text-align:left">
        <p>Neobvyklá událost. Pokud ani po 72 hodinách nedovedeme zjistit stav rezervace.
          V praxi zatím nenastalo.</p>
        <p>Pro zákazníka znamená: Rezervace se nepovedla.</p>
        <p>Pro agenturu znamená: Je nutné vrátit peníze.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Travelfusion Rezervace neúspěšná</b>
      </td>
      <td style="text-align:left">
        <p>Neobvyklá událost. Rezervace odmítnutá.</p>
        <p>Pro zákazníka znamená: Rezervace se nepovedla.</p>
        <p>Pro agenturu znamená: Je nutné vrátit peníze.</p>
      </td>
    </tr>
  </tbody>
</table>