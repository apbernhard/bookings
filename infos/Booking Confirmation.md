# Main part

| type  | `div`          |
| ----- | -------------- |
| class | `main-content` |

## Booking details

### Booking nr.

| type  | `span`             |
| ----- | ------------------ |
| class | `book-num__digits` |

## Hotel details

| type  | `div`                    |
| ----- | ------------------------ |
| class | `hotel-details__address` |

### Name

| type  | `h2`         |
| ----- | ------------ |
| class | `marginTop5` |

### address

| type  | `div`                                                                                                           |
| ----- | --------------------------------------------------------------------------------------------------------------- |
| class | `marginTop5`                                                                                                    |
| extra | Text between `</strong>` and `<br>`<br/><strong>Address:</strong> Douar Ain Lamdiour, Taroudant, 83000, Morocco |

#### GPS

| type  | `div`                                                                                                                        |
| ----- | ---------------------------------------------------------------------------------------------------------------------------- |
| class | `marginTop2`                                                                                                                 |
| extra | Second item of this class in object address; like address: `<strong>`GPS Coordinates:`</strong>` N 030° 24.805, W 08° 53.664 |

## Units and nights

| type  | `div`                      |
| ----- | -------------------------- |
| class | `col-5 rooms-nights__item` |

### units

| type  | `span`             |
| ----- | ------------------ |
| class | `summary__big-num` |

## Room item

| type  | `div`                                         |
| ----- | --------------------------------------------- |
| class | `main-content__item room`                     |
| extra | no. of items of this class should match units |

### room infos

| type  | `div`        |
| ----- | ------------ |
| class | `room__info` |

#### room category

| type | `h2` |
| ---- | ---- |

#### guests

| type  | `div`                                                                                                                                            |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| class | `room__info`                                                                                                                                     |
| extra | first occurence of `<strong>`; guests are between items `<strong>`Name des Gastes:`</strong><br/>` and `/` <br/>guest names are separated by `;` |

#### meal

| type  | div                                                                                       |
| ----- | ----------------------------------------------------------------------------------------- |
| class | `room__info`                                                                              |
| extra | second item between `<strong>` tags<br/>`<strong>`Verpflegung:`</strong>`<br/> and `<br>` |

   
