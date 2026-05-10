namespace JupiterMission {
    open Microsoft.Quantum.Intrinsic;
    open Microsoft.Quantum.Canon;

    operation CodexJupiterMission() : Unit {
        Message("🚀 Launching Codex Jupiter Mission...");

        // Allocate qubits for spacecraft and moons
        using (spacecraft = Qubit()) {
        using (europa = Qubit()) {
        using (io = Qubit()) {
        using (ganimedes = Qubit()) {
        using (calisto = Qubit()) {

            // --- Stage 1: Initialization ---
            Message("Stage 1: Initializing spacecraft trajectory...");
            H(spacecraft);
            Rz(0.5, spacecraft);

            // --- Stage 2: Destination Superposition ---
            Message("Stage 2: Setting possible destinations...");
            H(europa);
            H(io);
            H(ganimedes);
            H(calisto);

            // --- Stage 3: Gravity Assist Maneuvers ---
            Message("Stage 3: Performing gravity assists...");
            Rz(0.25, europa);
            Rz(0.50, io);
            Rz(0.75, ganimedes);
            Rz(1.00, calisto);

            Rx(0.33, europa);
            Rx(0.66, io);
            Rx(0.99, ganimedes);
            Rx(1.22, calisto);

            // --- Stage 4: Entanglement of Destinations ---
            Message("Stage 4: Entangling destinations to simulate orbital interactions...");
            CNOT(europa, io);
            CNOT(ganimedes, calisto);

            // --- Stage 5: Mission Decisions ---
            Message("Stage 5: Measuring outcomes...");
            let resultSpacecraft = M(spacecraft);
            let resultEuropa = M(europa);
            let resultIo = M(io);
            let resultGanimedes = M(ganimedes);
            let resultCalisto = M(calisto);

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

            if (resultGanimedes == Zero) {
                Message("Mission reached Ganymede 🛰️ - magnetic field detected.");
            } else {
                Message("Ganymede was not reached.");
            }

            if (resultCalisto == Zero) {
                Message("Mission reached Callisto 🪐 - ancient cratered surface mapped.");
            } else {
                Message("Callisto was not reached.");
            }

            // --- Stage 7: Extended Exploration ---
            Message("Stage 7: Extended exploration maneuvers...");
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

            // --- Stage 9: Mission Conclusion ---
            Message("Stage 9: Concluding mission...");
            Reset(spacecraft);
            Reset(europa);
            Reset(io);
            Reset(ganimedes);
            Reset(calisto);

            Message("✅ Codex Jupiter Mission completed.");
        }}}}}
    }
}
