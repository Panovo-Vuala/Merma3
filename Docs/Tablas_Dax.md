| TableID | Name                                                   | QueryDEFINITION                                                                                                        |
| ------- | ------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| 13      | Calendario                                             | CALENDAR (DATE(2024, 1, 1), DATE(2025, 12, 31))                                                                        |
| 16      | DateTableTemplate_3d4bff25-d899-4581-952c-9f45620ad42a | Calendar(Date(2015,1,1), Date(2015,1,1))                                                                               |
| 19      | LocalDateTable_b57b699b-868a-4c64-a646-f36c82a37b33    | Calendar(Date(Year(MIN('Calendario'[Date])), 1, 1), Date(Year(MAX('Calendario'[Date])), 12, 31))                       |
| 63000   | TablaSemanas                                           | DISTINCT( Calendario[semana] )                                                                                         |
| 110847  | LocalDateTable_befac165-601d-4191-b5e7-65d7f9236876    | Calendar(Date(Year(MIN('BD_AppMerma'[FechaHora])), 1, 1), Date(Year(MAX('BD_AppMerma'[FechaHora])), 12, 31))           |
| 113484  | LocalDateTable_2a4820d6-ce04-4aa0-855a-d491dee4df00    | Calendar(Date(Year(MIN('BD_AppMerma'[Fecha])), 1, 1), Date(Year(MAX('BD_AppMerma'[Fecha])), 12, 31))                   |
| 144343  | LocalDateTable_6e5ab373-b704-45d7-a65e-0a4478d29613    | Calendar(Date(Year(MIN('metrics_v2'[created_at])), 1, 1), Date(Year(MAX('metrics_v2'[created_at])), 12, 31))           |
| 144346  | LocalDateTable_1c83ad4e-c516-4604-b160-7a11cc36d571    | Calendar(Date(Year(MIN('metrics_v2'[updated_at])), 1, 1), Date(Year(MAX('metrics_v2'[updated_at])), 12, 31))           |
| 144349  | LocalDateTable_5d0e57a5-2bb6-465d-a289-4acc7bedb5f8    | Calendar(Date(Year(MIN('metrics_v2'[_version])), 1, 1), Date(Year(MAX('metrics_v2'[_version])), 12, 31))               |
| 144352  | LocalDateTable_0db5fe57-3890-4ab9-ba39-1140d025dd90    | Calendar(Date(Year(MIN('metrics_v2'[last_reading_at])), 1, 1), Date(Year(MAX('metrics_v2'[last_reading_at])), 12, 31)) |
