### Navigation Documentation (Mobile)
- Main navigation uses URL parameters. Parameter "state" determines
  which page will show. state should always evaluate to one of the
  options within the option set "curent page"
- specific groups, churches,events and profiles use the parameter "group"
  "church" "event" or "profile" respectively. The paramter should
  evaluate to  a unique ID.
### Sub Navigation (mobile)
- many pages have navigation within which do not use a parameter change.
  These use state changes. The larger page group holding the sub groups
  is the only one which has a state change. In the case of profile sub navigation,
  the state is named "profile nav" this state should always evaluate to an option
  from the option set "profile sub nav" Each element group within profile is set to
  hide or reveal depending on profile's profile nav state. This is set within the conditions tab.
