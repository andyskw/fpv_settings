FPV drone Betaflight settings
=============================

This repository contains Betaflight settings for various owned FPV drones. When I purchased my first - and currently only - FPV drone, I realised, finding everything in one place to reset my drone to a nearly-factory setting was a pretty hard time.

I am a beginner FPV pilot, so my settings are mostly for beginner setup at this point.

Emax TinyHawk 2
---------------
 * Location: EU
 * Updated firmware to 4.2.0 on Betaflight Configurator 10.7.0. Version info:
 > Betaflight / STM32F411 (S411) **4.2.0** Jun 14 2020 / 03:04:43 (8f2d21460) MSP API: 1.43
 config: manufacturer_id: MTKS, board_name: MATEKF411RX, version: ee671311, date: 2019-10-16T11:49:37Z
 board: manufacturer_id: MTKS, board_name: MATEKF411RX
 * VTX: 
   * Power level 25 and 100 added
   * transmitting on RACEBAND channel 4 (instead of the default)
 * PID settings are default, Horizon mode angle limit is set to 20 degree
 * beeper theme 
 * 2S battery PID and rate profiles may not be correct, please validate it before using (and send PR in case if you need fix!)
 
 After using these configurations, you may need to:
  * Set up the vtx channels on your goggles
  * Recalibrate accelerometer