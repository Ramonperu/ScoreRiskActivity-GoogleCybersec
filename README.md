# ScoreRiskActivity-GoogleCybersec

Se nos ha proporcionado un escenario para hacer una valoracion de la prioridad de ciertos activos dentro de una empresa, la plantilla es [esta](https://github.com/Ramonperu/ScoreRiskActivity-GoogleCybersec/blob/main/Risk-register.docx).



| **Asset** | **Risk(s)**               | **Description**                                              | **Likelihood** | **Severity** | **Priority** |
| --------- | ------------------------- | ------------------------------------------------------------ | -------------- | ------------ | ------------ |
| Funds     | Business email compromise | An employee is tricked into sharing confidential information. | 2              | 3            | 6            |
| Funds     | Compromised user database | Customer data is poorly encrypted.                           | 2              | 3            | 6            |
| Funds     | Financial records leak    | A database server of backed up data is publicly accessible.  | 3              | 3            | 9            |
| Funds     | Theft                     | The bank's safe is left unlocked.                            | 1              | 2            | 2            |
| Funds     | Supply chain disruption   | Delivery delays due to natural disasters.                    | 1              | 2            | 2            |

### Justificación de los puntuación:

1. **Business Email Compromise**:
   - **Likelihood (2)**: Medi probabilidad dado el número de empleados y la sofisticación de los ataques de phishing.
   - **Severity (3)**: Puede causar un daño significativo, como el acceso no autorizado a información sensible o fondos.
   - **Priority (6)**: Riesgo importante
2. **Compromised User Database**:
   - **Likelihood (2)**: Alta probabilidad debido al volumen de datos y la posibilidad de configuraciones de seguridad incorrectas.
   - **Severity (3)**: La exposición de datos puede llevar a pérdidas financieras significativas, sanciones regulatorias y daño reputacional.
   - **Priority (6)**: Riesgo importante requiere atencion pero no inmediata.
3. **Financial Records Leak**:
   - **Likelihood (2)**: Moderada probabilidad, dependiendo de las medidas de seguridad actuales.
   - **Severity (3)**: La fuga de datos financieros podría llevar a multas, pérdida de confianza de los clientes y repercusiones legales.
   - **Priority (9)**: Requiere atencion inmediata.
4. **Theft**:
   - **Likelihood (1)**: Baja probabilidad, especialmente con bajos índices de criminalidad y medidas de seguridad física en su lugar.
   - **Severity (2)**: Impacto moderado si ocurre, pero es manejable.
   - **Priority (2)**: Menor prioridad dado que es menos probable y tiene un impacto más bajo.
5. **Supply Chain Disruption**:
   - **Likelihood (1)**: Moderada probabilidad, especialmente en una ubicación costera propensa a desastres naturales.
   - **Severity (2)**: Impacto moderado en las operaciones diarias, pero manejable con planes de contingencia.
   - **Priority (2)**: Prioridad baja ya que podria afectar pero no es probable que suceda