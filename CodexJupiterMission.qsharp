namespace CodexJupiterMission {
    open Microsoft.Quantum.Intrinsic;
    open Microsoft.Quantum.Canon;

    operation RunMission() : Unit {
        Message("🚀 Launching Codex Jupiter Mission...");

        // --- Stage 1: Spacecraft Initialization ---
        using (spacecraft = Qubit()) {
            Message("Stage 1: Initializing spacecraft trajectory...");
            H(spacecraft);
            Rz(0.5, spacecraft);

            // --- Stage 2: Destination Setup ---
            using (europa = Qubit()) {
            using (io = Qubit()) {
            using (ganymede = Qubit()) {
            using (callisto = Qubit()) {

                Message("Stage 2: Setting possible destinations...");
                H(europa);
                H(io);
                H(ganymede);
                H(callisto);

                // --- Stage 3: Gravity Assists ---
                Message("Stage 3: Performing gravity assists...");
                Rz(0.25, europa);
                Rz(0.50, io);
                Rz(0.75, ganymede);
                Rz(1.00, callisto);

                Rx(0.33, europa);
                Rx(0.66, io);
                Rx(0.99, ganymede);
                Rx(1.22, callisto);

                // --- Stage 4: Orbital Entanglement ---
                Message("Stage 4: Entangling destinations to simulate orbital interactions...");
                CNOT(europa, io);
                CNOT(ganymede, callisto);

                // --- Stage 5: Mission Decisions ---
                Message("Stage 5: Measuring outcomes...");
                let resultSpacecraft = M(spacecraft);
                let resultEuropa = M(europa);
                let resultIo = M(io);
                let resultGanymede = M(ganymede);
                let resultCallisto = M(callisto);

                // --- Stage 6: Reporting ---
                Message("Stage 6: Reporting mission results...");
                if (resultSpacecraft == Zero) {
                    Message("Spacecraft maintained stable trajectory.");
                } else {
                    Message("Spacecraft experienced trajectory deviation.");
                }

                if (resultEuropa == Zero) {
                    Message("Mission reached Europa 🌊 - subsurface ocean detected.");
                } else {
                    Message("Europa was not reached.");
                }

                if (resultIo == Zero) {
                    Message("Mission reached Io 🌋 - volcanic activity observed.");
                } else {
                    Message("Io was not reached.");
                }

                if (resultGanymede == Zero) {
                    Message("Mission reached Ganymede 🛰️ - magnetic field detected.");
                } else {
                    Message("Ganymede was not reached.");
                }

                if (resultCallisto == Zero) {
                    Message("Mission reached Callisto 🪐 - ancient cratered surface mapped.");
                } else {
                    Message("Callisto was not reached.");
                }

                // --- Stage 7: Deploy Extra Probe ---
                Message("Stage 7: Deploying extra probe...");
                using (extraProbe = Qubit()) {
                    H(extraProbe);
                    Rz(0.45, extraProbe);
                    let probeResult = M(extraProbe);

                    if (probeResult == Zero) {
                        Message("Extra probe successfully deployed to orbit Europa.");
                    } else {
                        Message("Extra probe diverted to orbit Io.");
                    }

                    Reset(extraProbe);
                }

                // --- Stage 8: Science Experiments ---
                Message("Stage 8: Conducting science experiments...");
                using (experiment = Qubit()) {
                    H(experiment);
                    Rx(0.75, experiment);
                    let experimentResult = M(experiment);

                    if (experimentResult == Zero) {
                        Message("Experiment detected organic molecules.");
                    } else {
                        Message("Experiment detected high radiation levels.");
                    }

                    Reset(experiment);
                }

                // --- Stage 9: Extended Exploration ---
                Message("Stage 9: Extended exploration maneuvers...");
                using (survey = Qubit()) {
                    H(survey);
                    Rz(1.5, survey);
                    let surveyResult = M(survey);

                    if (surveyResult == Zero) {
                        Message("Survey mapped ice fractures on Europa.");
                    } else {
                        Message("Survey mapped volcanic plumes on Io.");
                    }

                    Reset(survey);
                }

                // --- Stage 10: Mission Conclusion ---
                Message("Stage 10: Concluding mission...");
                Reset(spacecraft);
                Reset(europa);
                Reset(io);
                Reset(ganymede);
                Reset(callisto);

                Message("✅ Codex Jupiter Mission completed.");
            }}}}
        }
    }
}
