# 🔐 CipherForgeA 5-phase encryption algorithm built from scratch in Python.📋 DescriptionCipherForge is an educational encryption system that demonstrates how real-world encryption algorithms like AES work. It applies 5 layers of transformation to convert plaintext into unreadable ciphertext.✨ Features5-phase encryption pipelineWeb interface for easy encryption/decryptionKey-based security with trillions of combinationsAutomated test suite for verification🔧 The 5 PhasesPhaseNameDescription1SubstitutionShifts all characters by a fixed amount2TranspositionReverses characters in blocks3Key-DependentUses password for variable shifting4Noise InjectionAdds decoy characters5Wild Card[YOUR DESCRIPTION HERE]🚀 Getting StartedRun in CodespacesClick Code → Codespaces → Create codespaceWait for environment to loadRun: python app.pyOpen the Ports tab and click the globe icon for port 5000Run Testspython test_engine.py
🔑 Key FormatThe encryption key is a dictionary with these fields:key = {
    "shift": 5,              # Phase 1: shift amount (1-94)
    "block_size": 4,         # Phase 2: block size (2-20)
    "password": "SECRET",    # Phase 3: encryption password
    "noise_interval": 3,     # Phase 4: insert noise every N chars
    "noise_char": "~"        # Phase 4: noise character to insert
}
📊 Security AnalysisStrengthsMulti-layer encryption defeats simple attacksPassword-based encryption provides large key spaceNoise injection defeats frequency analysisWeaknesses (Educational Context)Not mathematically proven like AESSmaller key space than production encryptionVulnerable to known-plaintext attacks with enough samples📝 LicenseMIT License - see LICENSE file👤 Author[YOUR NAME] - [YOUR SCHOOL] - 2026
Built as part of Year 9 Digital Technologies
