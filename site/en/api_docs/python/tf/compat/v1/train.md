page_type: reference
<style>{% include "site-assets/css/style.css" %}</style>

<!-- DO NOT EDIT! Automatically generated file. -->

# Module: tf.compat.v1.train


<table class="tfo-notebook-buttons tfo-api" align="left">
</table>



Support for training models.

<!-- Placeholder for "Used in" -->

See the [Training](https://tensorflow.org/api_guides/python/train) guide.

## Modules

[`experimental`](../../../tf/compat/v1/train/experimental) module: Public API for tf.train.experimental namespace.

[`queue_runner`](../../../tf/compat/v1/train/queue_runner) module: Public API for tf.train.queue_runner namespace.

## Classes

[`class AdadeltaOptimizer`](../../../tf/compat/v1/train/AdadeltaOptimizer): Optimizer that implements the Adadelta algorithm.

[`class AdagradDAOptimizer`](../../../tf/compat/v1/train/AdagradDAOptimizer): Adagrad Dual Averaging algorithm for sparse linear models.

[`class AdagradOptimizer`](../../../tf/compat/v1/train/AdagradOptimizer): Optimizer that implements the Adagrad algorithm.

[`class AdamOptimizer`](../../../tf/compat/v1/train/AdamOptimizer): Optimizer that implements the Adam algorithm.

[`class BytesList`](../../../tf/train/BytesList): A ProtocolMessage

[`class Checkpoint`](../../../tf/compat/v1/train/Checkpoint): Groups trackable objects, saving and restoring them.

[`class CheckpointManager`](../../../tf/train/CheckpointManager): Deletes old checkpoints.

[`class CheckpointSaverHook`](../../../tf/estimator/CheckpointSaverHook): Saves checkpoints every N steps or seconds.

[`class CheckpointSaverListener`](../../../tf/estimator/CheckpointSaverListener): Interface for listeners that take action before or after checkpoint save.

[`class ChiefSessionCreator`](../../../tf/compat/v1/train/ChiefSessionCreator): Creates a tf.compat.v1.Session for a chief.

[`class ClusterDef`](../../../tf/train/ClusterDef): A ProtocolMessage

[`class ClusterSpec`](../../../tf/train/ClusterSpec): Represents a cluster as a set of "tasks", organized into "jobs".

[`class Coordinator`](../../../tf/train/Coordinator): A coordinator for threads.

[`class Example`](../../../tf/train/Example): A ProtocolMessage

[`class ExponentialMovingAverage`](../../../tf/train/ExponentialMovingAverage): Maintains moving averages of variables by employing an exponential decay.

[`class Feature`](../../../tf/train/Feature): A ProtocolMessage

[`class FeatureList`](../../../tf/train/FeatureList): A ProtocolMessage

[`class FeatureLists`](../../../tf/train/FeatureLists): A ProtocolMessage

[`class Features`](../../../tf/train/Features): A ProtocolMessage

[`class FeedFnHook`](../../../tf/estimator/FeedFnHook): Runs `feed_fn` and sets the `feed_dict` accordingly.

[`class FinalOpsHook`](../../../tf/estimator/FinalOpsHook): A hook which evaluates `Tensors` at the end of a session.

[`class FloatList`](../../../tf/train/FloatList): A ProtocolMessage

[`class FtrlOptimizer`](../../../tf/compat/v1/train/FtrlOptimizer): Optimizer that implements the FTRL algorithm.

[`class GlobalStepWaiterHook`](../../../tf/estimator/GlobalStepWaiterHook): Delays execution until global step reaches `wait_until_step`.

[`class GradientDescentOptimizer`](../../../tf/compat/v1/train/GradientDescentOptimizer): Optimizer that implements the gradient descent algorithm.

[`class Int64List`](../../../tf/train/Int64List): A ProtocolMessage

[`class JobDef`](../../../tf/train/JobDef): A ProtocolMessage

[`class LoggingTensorHook`](../../../tf/estimator/LoggingTensorHook): Prints the given tensors every N local steps, every N seconds, or at end.

[`class LooperThread`](../../../tf/compat/v1/train/LooperThread): A thread that runs code repeatedly, optionally on a timer.

[`class MomentumOptimizer`](../../../tf/compat/v1/train/MomentumOptimizer): Optimizer that implements the Momentum algorithm.

[`class MonitoredSession`](../../../tf/compat/v1/train/MonitoredSession): Session-like object that handles initialization, recovery and hooks.

[`class NanLossDuringTrainingError`](../../../tf/estimator/NanLossDuringTrainingError): Unspecified run-time error.

[`class NanTensorHook`](../../../tf/estimator/NanTensorHook): Monitors the loss tensor and stops training if loss is NaN.

[`class Optimizer`](../../../tf/compat/v1/train/Optimizer): Base class for optimizers.

[`class ProfilerHook`](../../../tf/estimator/ProfilerHook): Captures CPU/GPU profiling information every N steps or seconds.

[`class ProximalAdagradOptimizer`](../../../tf/compat/v1/train/ProximalAdagradOptimizer): Optimizer that implements the Proximal Adagrad algorithm.

[`class ProximalGradientDescentOptimizer`](../../../tf/compat/v1/train/ProximalGradientDescentOptimizer): Optimizer that implements the proximal gradient descent algorithm.

[`class QueueRunner`](../../../tf/compat/v1/train/QueueRunner): Holds a list of enqueue operations for a queue, each to be run in a thread.

[`class RMSPropOptimizer`](../../../tf/compat/v1/train/RMSPropOptimizer): Optimizer that implements the RMSProp algorithm.

[`class Saver`](../../../tf/compat/v1/train/Saver): Saves and restores variables.

[`class SaverDef`](../../../tf/compat/v1/train/SaverDef): A ProtocolMessage

[`class Scaffold`](../../../tf/compat/v1/train/Scaffold): Structure to create or gather pieces commonly needed to train a model.

[`class SecondOrStepTimer`](../../../tf/estimator/SecondOrStepTimer): Timer that triggers at most once every N seconds or once every N steps.

[`class SequenceExample`](../../../tf/train/SequenceExample): A ProtocolMessage

[`class Server`](../../../tf/distribute/Server): An in-process TensorFlow server, for use in distributed training.

[`class ServerDef`](../../../tf/train/ServerDef): A ProtocolMessage

[`class SessionCreator`](../../../tf/compat/v1/train/SessionCreator): A factory for tf.Session.

[`class SessionManager`](../../../tf/compat/v1/train/SessionManager): Training helper that restores from checkpoint and creates session.

[`class SessionRunArgs`](../../../tf/estimator/SessionRunArgs): Represents arguments to be added to a `Session.run()` call.

[`class SessionRunContext`](../../../tf/estimator/SessionRunContext): Provides information about the `session.run()` call being made.

[`class SessionRunHook`](../../../tf/estimator/SessionRunHook): Hook to extend calls to MonitoredSession.run().

[`class SessionRunValues`](../../../tf/estimator/SessionRunValues): Contains the results of `Session.run()`.

[`class SingularMonitoredSession`](../../../tf/compat/v1/train/SingularMonitoredSession): Session-like object that handles initialization, restoring, and hooks.

[`class StepCounterHook`](../../../tf/estimator/StepCounterHook): Hook that counts steps per second.

[`class StopAtStepHook`](../../../tf/estimator/StopAtStepHook): Hook that requests stop at a specified step.

[`class SummarySaverHook`](../../../tf/estimator/SummarySaverHook): Saves summaries every N steps.

[`class Supervisor`](../../../tf/compat/v1/train/Supervisor): A training helper that checkpoints models and computes summaries.

[`class SyncReplicasOptimizer`](../../../tf/compat/v1/train/SyncReplicasOptimizer): Class to synchronize, aggregate gradients and pass them to the optimizer.

[`class VocabInfo`](../../../tf/estimator/VocabInfo): Vocabulary information for warm-starting.

[`class WorkerSessionCreator`](../../../tf/compat/v1/train/WorkerSessionCreator): Creates a tf.compat.v1.Session for a worker.

## Functions

[`MonitoredTrainingSession(...)`](../../../tf/compat/v1/train/MonitoredTrainingSession): Creates a `MonitoredSession` for training.

[`NewCheckpointReader(...)`](../../../tf/compat/v1/train/NewCheckpointReader)

[`add_queue_runner(...)`](../../../tf/compat/v1/train/add_queue_runner): Adds a `QueueRunner` to a collection in the graph. (deprecated)

[`assert_global_step(...)`](../../../tf/compat/v1/train/assert_global_step): Asserts `global_step_tensor` is a scalar int `Variable` or `Tensor`.

[`basic_train_loop(...)`](../../../tf/compat/v1/train/basic_train_loop): Basic loop to train a model.

[`batch(...)`](../../../tf/compat/v1/train/batch): Creates batches of tensors in `tensors`. (deprecated)

[`batch_join(...)`](../../../tf/compat/v1/train/batch_join): Runs a list of tensors to fill a queue to create batches of examples. (deprecated)

[`checkpoint_exists(...)`](../../../tf/compat/v1/train/checkpoint_exists): Checks whether a V1 or V2 checkpoint exists with the specified prefix. (deprecated)

[`checkpoints_iterator(...)`](../../../tf/train/checkpoints_iterator): Continuously yield new checkpoint files as they appear.

[`cosine_decay(...)`](../../../tf/compat/v1/train/cosine_decay): Applies cosine decay to the learning rate.

[`cosine_decay_restarts(...)`](../../../tf/compat/v1/train/cosine_decay_restarts): Applies cosine decay with restarts to the learning rate.

[`create_global_step(...)`](../../../tf/compat/v1/train/create_global_step): Create global step tensor in graph.

[`do_quantize_training_on_graphdef(...)`](../../../tf/compat/v1/train/do_quantize_training_on_graphdef): A general quantization scheme is being developed in `tf.contrib.quantize`. (deprecated)

[`exponential_decay(...)`](../../../tf/compat/v1/train/exponential_decay): Applies exponential decay to the learning rate.

[`export_meta_graph(...)`](../../../tf/compat/v1/train/export_meta_graph): Returns `MetaGraphDef` proto.

[`generate_checkpoint_state_proto(...)`](../../../tf/compat/v1/train/generate_checkpoint_state_proto): Generates a checkpoint state proto.

[`get_checkpoint_mtimes(...)`](../../../tf/compat/v1/train/get_checkpoint_mtimes): Returns the mtimes (modification timestamps) of the checkpoints. (deprecated)

[`get_checkpoint_state(...)`](../../../tf/train/get_checkpoint_state): Returns CheckpointState proto from the "checkpoint" file.

[`get_global_step(...)`](../../../tf/compat/v1/train/get_global_step): Get the global step tensor.

[`get_or_create_global_step(...)`](../../../tf/compat/v1/train/get_or_create_global_step): Returns and create (if necessary) the global step tensor.

[`global_step(...)`](../../../tf/compat/v1/train/global_step): Small helper to get the global step.

[`import_meta_graph(...)`](../../../tf/compat/v1/train/import_meta_graph): Recreates a Graph saved in a `MetaGraphDef` proto.

[`init_from_checkpoint(...)`](../../../tf/compat/v1/train/init_from_checkpoint): Replaces <a href="../../../tf/Variable"><code>tf.Variable</code></a> initializers so they load from a checkpoint file.

[`input_producer(...)`](../../../tf/compat/v1/train/input_producer): Output the rows of `input_tensor` to a queue for an input pipeline. (deprecated)

[`inverse_time_decay(...)`](../../../tf/compat/v1/train/inverse_time_decay): Applies inverse time decay to the initial learning rate.

[`latest_checkpoint(...)`](../../../tf/train/latest_checkpoint): Finds the filename of latest saved checkpoint file.

[`limit_epochs(...)`](../../../tf/compat/v1/train/limit_epochs): Returns tensor `num_epochs` times and then raises an `OutOfRange` error. (deprecated)

[`linear_cosine_decay(...)`](../../../tf/compat/v1/train/linear_cosine_decay): Applies linear cosine decay to the learning rate.

[`list_variables(...)`](../../../tf/train/list_variables): Returns list of all variables in the checkpoint.

[`load_checkpoint(...)`](../../../tf/train/load_checkpoint): Returns `CheckpointReader` for checkpoint found in `ckpt_dir_or_file`.

[`load_variable(...)`](../../../tf/train/load_variable): Returns the tensor value of the given variable in the checkpoint.

[`match_filenames_once(...)`](../../../tf/io/match_filenames_once): Save the list of files matching pattern, so it is only computed once.

[`maybe_batch(...)`](../../../tf/compat/v1/train/maybe_batch): Conditionally creates batches of tensors based on `keep_input`. (deprecated)

[`maybe_batch_join(...)`](../../../tf/compat/v1/train/maybe_batch_join): Runs a list of tensors to conditionally fill a queue to create batches. (deprecated)

[`maybe_shuffle_batch(...)`](../../../tf/compat/v1/train/maybe_shuffle_batch): Creates batches by randomly shuffling conditionally-enqueued tensors. (deprecated)

[`maybe_shuffle_batch_join(...)`](../../../tf/compat/v1/train/maybe_shuffle_batch_join): Create batches by randomly shuffling conditionally-enqueued tensors. (deprecated)

[`natural_exp_decay(...)`](../../../tf/compat/v1/train/natural_exp_decay): Applies natural exponential decay to the initial learning rate.

[`noisy_linear_cosine_decay(...)`](../../../tf/compat/v1/train/noisy_linear_cosine_decay): Applies noisy linear cosine decay to the learning rate.

[`piecewise_constant(...)`](../../../tf/compat/v1/train/piecewise_constant): Piecewise constant from boundaries and interval values.

[`piecewise_constant_decay(...)`](../../../tf/compat/v1/train/piecewise_constant): Piecewise constant from boundaries and interval values.

[`polynomial_decay(...)`](../../../tf/compat/v1/train/polynomial_decay): Applies a polynomial decay to the learning rate.

[`range_input_producer(...)`](../../../tf/compat/v1/train/range_input_producer): Produces the integers from 0 to limit-1 in a queue. (deprecated)

[`remove_checkpoint(...)`](../../../tf/compat/v1/train/remove_checkpoint): Removes a checkpoint given by `checkpoint_prefix`. (deprecated)

[`replica_device_setter(...)`](../../../tf/compat/v1/train/replica_device_setter): Return a `device function` to use when building a Graph for replicas.

[`sdca_fprint(...)`](../../../tf/compat/v1/train/sdca_fprint): Computes fingerprints of the input strings.

[`sdca_optimizer(...)`](../../../tf/compat/v1/train/sdca_optimizer): Distributed version of Stochastic Dual Coordinate Ascent (SDCA) optimizer for

[`sdca_shrink_l1(...)`](../../../tf/compat/v1/train/sdca_shrink_l1): Applies L1 regularization shrink step on the parameters.

[`shuffle_batch(...)`](../../../tf/compat/v1/train/shuffle_batch): Creates batches by randomly shuffling tensors. (deprecated)

[`shuffle_batch_join(...)`](../../../tf/compat/v1/train/shuffle_batch_join): Create batches by randomly shuffling tensors. (deprecated)

[`slice_input_producer(...)`](../../../tf/compat/v1/train/slice_input_producer): Produces a slice of each `Tensor` in `tensor_list`. (deprecated)

[`start_queue_runners(...)`](../../../tf/compat/v1/train/start_queue_runners): Starts all queue runners collected in the graph. (deprecated)

[`string_input_producer(...)`](../../../tf/compat/v1/train/string_input_producer): Output strings (e.g. filenames) to a queue for an input pipeline. (deprecated)

[`summary_iterator(...)`](../../../tf/compat/v1/train/summary_iterator): An iterator for reading `Event` protocol buffers from an event file.

[`update_checkpoint_state(...)`](../../../tf/compat/v1/train/update_checkpoint_state): Updates the content of the 'checkpoint' file. (deprecated)

[`warm_start(...)`](../../../tf/compat/v1/train/warm_start): Warm-starts a model using the given settings.

[`write_graph(...)`](../../../tf/io/write_graph): Writes a graph proto to a file.