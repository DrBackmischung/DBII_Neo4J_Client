MATCH p=()-->() RETURN 
MATCH p=()-->() RETURN p LIMIT 25
MATCH (n:Person) WHERE n.name = 'Danny DeVito' RETURN n
MATCH (n:Person{name: 'Danny DeVito'}) RETURN n 
MATCH (n:Person{name: 'Danny DeVito'})-->(m:Movie) RETURN n, m
MATCH (n:Person{name: 'Danny DeVito'})-[:ACTED_IN]->(m:Movie) RETURN n, m
MATCH (n:Person{name: 'Danny DeVito'})-[:DIRECTED]->(m:Movie) RETURN n, m
MATCH (m:Movie{name: 'The Matrix'})-[:ACTED_IN]->(n:Person) RETURN m, n
