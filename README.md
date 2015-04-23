## Moving things from a place to another place.

![schema](schema.jpg)

### Purpose

Purposely, the goal of this repository is to organize things to make them fit the way they have to be fitted.
Two people needs to move things from a place (more precisely: two places) into another completely different place.
This repos is gonna making things accords themselves by assembling the tasks to be done and the people who agree to do them.

### Syntax

```
  #team<int>   Name of the team, index matches /[1-4]/
  #p<int>      Name of the place, index matches /[1-4]/
  !J           Person 1 who want things to be moved
  !M           Person 2 who want things to be moved
  !<int>       People helping to move things. Index matches /[0-9]/
               See "People matching" section below
```

### Map of actions, indexed by timestamp

<table>
  <thead>
    <tr>
      <th></th>
      <th><code>#team1</code></th>
      <th><code>#team2</code></th>
      <th><code>#team3</code></th>
      <th><code>#team4</code></th>
    </tr>
  </thead>
  <tbody>

    <tr>
      <td> <code>09:00</code>                                              </td>
      <td> <code>#p1</code> :flushed: Wake up                              </td>
      <td> <code>#p2</code> :flushed: Wake up                              </td>
      <td> <code>#p3</code> :sleeping: Sleep                               </td>
      <td> <code>#p4</code> :sleeping: Sleep                               </td>
    </tr>

    <tr>
      <td> <code>10:00</code>                                              </td>
      <td>                  :car: Go rent the car                          </td>
      <td> <code>#p2</code> :package: Move things from up to floor         </td>
      <td> <code>#p3</code> :flushed: Wake up                              </td>
      <td> <code>#p4</code> :flushed: Wake up                              </td>
    </tr>

    <tr>
      <td> <code>11:00</code>                                              </td>
      <td> <code>#p2</code> :package: Move things from floor to car        </td>
      <td> <code>#p2</code> :package: Move things from floor to car        </td>
      <td>                  :trolleybus: Move from one place to another    </td>
      <td> <code>#p4</code> :no_mouth: Do absolutely nothing               </td>
    </tr>

  </tbody>
</table>
