# IpEditBehavior
IP Address editing WPF behavior for TextBox element.
Prevents entering incorrect IP addresses into attached TextBox

Usage (Requires System.Windows.Interactivity):
```XAML
<TextBox Margin="10" Text="192.168.100.27">
  <i:Interaction.Behaviors>
    <ipedit:IpEditBehavior />
  </i:Interaction.Behaviors>
</TextBox>
```
