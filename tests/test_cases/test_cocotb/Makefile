# Copyright cocotb contributors
# Licensed under the Revised BSD License, see LICENSE for details.
# SPDX-License-Identifier: BSD-3-Clause

include ../../designs/sample_module/Makefile

MODULE := "\
	test_deprecated,\
	test_synchronization_primitives,\
	test_concurrency_primitives,\
	test_tests,\
	test_testfactory,\
	test_generator_coroutines,\
	test_timing_triggers,\
	test_scheduler,\
	test_clock,\
	test_edge_triggers,\
	test_async_coroutines,\
	test_async_generators,\
	test_handle,\
	test_logging,\
	test_pytest,\
	test_queues,\
	test_utils,\
	test_fork,\
	"

ifeq ($(SIM),questa)
	SIM_ARGS := "-t ps"
endif
