SCHEMACHECK=	python3 ../scripts/schemacheck.py
SCHEMADIR=	../schemata

check:
	$(SCHEMACHECK) --input at_stop.json $(SCHEMADIR)/at_stop.yaml
	$(SCHEMACHECK) --input journey.json $(SCHEMADIR)/journey.yaml
	$(SCHEMACHECK) --input last_stop.json $(SCHEMADIR)/last_stop.yaml
	$(SCHEMACHECK) --input latest_ticket.json $(SCHEMADIR)/latest_ticket.yaml
	$(SCHEMACHECK) --input next_stop.json $(SCHEMADIR)/next_stop.yaml
	$(SCHEMACHECK) --input status.json $(SCHEMADIR)/status.yaml
	$(SCHEMACHECK) --input vehicle.json $(SCHEMADIR)/vehicle.yaml
	$(SCHEMACHECK) --input remaining_stops.json $(SCHEMADIR)/remaining_stops.yaml
	$(SCHEMACHECK) --input run_monitoring.json $(SCHEMADIR)/run_monitoring.yaml
